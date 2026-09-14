# Profile README — Design Variants

Six complete, self-contained designs for the `AhsanBilal7/AhsanBilal7` profile README. Every variant carries the **same information** (name, whoami, research keywords/venues, research focus, current work, contributions, selected publications, honors, toolbox, GitHub stats, and contact links) — only the visual style differs. No design shows a profile photo; identity is carried by the name heading and whoami line instead. Pick one and copy its content into the root `README.md`.

| # | File | Style | Palette |
|---|---|---|---|
| 1 | [`../README.md`](../README.md) *(live)* | **Signal** — clean academic-minimal, centered hero, tables | Blue `#2563EB` |
| 2 | [`design-terminal.md`](./design-terminal.md) | **Terminal** — dev/monospace, code-block sections, dark badges | Slate + electric blue `#0D1117` / `#58A6FF` |
| 3 | [`design-cards.md`](./design-cards.md) | **Cards** — Nord-inspired grid/table layout, collapsible toolbox | Nord `#3B4252` / `#88C0D0` / `#5E81AC` |
| 4 | [`design-retro.md`](./design-retro.md) | **Retro** — CRT terminal / phosphor-green nostalgia, ASCII header | Black + phosphor green `#0B0F0C` / `#39FF14` |
| 5 | [`design-research.md`](./design-research.md) | **Research** — formal faculty-page style, numbered citation list | Charcoal + academic burgundy `#7A1F3D` |
| 6 | [`design-visual.md`](./design-visual.md) | **Visual** — illustrates the research with 4 custom animated SVG diagrams (test-time search, gradient descent, RL loop, diffusion denoising) | Violet `#7C3AED` |

## How to switch the live design

```bash
cp designs/design-terminal.md README.md   # or any other design-*.md
git add README.md
git commit -m "Switch profile README design"
```

## Notes

- **No profile photo anywhere.** Earlier drafts embedded `ahsanbilal7.github.io/assets/images/ahsan_bilal.png`; it's been removed from all six designs per request — identity is carried by the `# Ahsan Bilal` heading + whoami line instead.
- **Compact, above-the-fold hero in every design.** Immediately under the name: a two-column layout with **Who I Am** (left) and **Research Keywords + Publishes In** (right) side by side, followed by a one-line **"Now:"** current-work snapshot linking down to the full Current Work section, then contact links. This puts identity, research focus, target venues, and current work all in view together, with detailed Current Work / Contributions / Publications / Honors / Toolbox following below. Research Focus itself was tightened from a paragraph to 4 short icon-led bullets.
- **Toolbox uses bigger icons.** All six designs now render their language/ML/infra/web/design stack as [skillicons.dev](https://skillicons.dev) icon grids (48px logos) instead of small text badges — theme-matched per design (dark for Terminal/Retro/Visual, light for Signal/Research, both via `<picture>` for Signal/Cards/Visual). Icon set: `py, cpp, c, java, matlab, pytorch, tensorflow, opencv, sklearn, docker, git, github, linux, vscode, aws, nginx, raspberrypi, react, nextjs, js, html, css, figma, xd, ai, ps, wordpress` — every slug verified against skillicons.dev's own icon list before use.
- **Techniques & tools without a logo** get their own compact text line below the icons rather than more badges: an **ML Techniques** line (GRPO, LoRA, ZeRO, Preference Optimization, Test-Time Scaling, LLM Post-Training, Agentic Systems) and an **Also** line (Statistical Learning Theory, Information Theory, MLflow, CUDA, Slurm, Cursor, Signal Processing, 5G, Distributed AI Systems, etc.). CUDA, Slurm, and Cursor were requested but aren't in skillicons.dev's curated icon set, so they're listed as text rather than silently dropped or shown as broken images.
- **Whitespace reduced throughout:** merged redundant "Who I Am" sections into the hero, dropped a contact-badge row in favor of small text links for secondary profiles (X, ORCID, Semantic Scholar, DBLP), shrank banner/typing-SVG heights, and removed stray blank lines between adjacent image blocks (stats/streak/activity-graph).
- **SVG entity bug, fixed and verified:** `capsule-render`'s `desc=`/`text=` params do **not** XML-escape a raw `&`, so a percent-encoded `%26` in those params comes back as a literal, un-escaped `&` inside the returned SVG's `<text>` node — confirmed by fetching the old header URL directly: `xmllint` reported `xmlParseEntityRef: no name` at line 43, exactly matching the error report. (`readme-typing-svg` was checked too and does escape correctly — `&amp;` — so it wasn't actually at fault, but every design still avoids `&` there as well, out of caution.) Fix: the main capsule-render banners are now decorative-only (no `desc=`/`text=`), and any remaining `&`-adjacent phrasing anywhere uses `·` instead — verified with `grep -rn '%26'` across all files (no matches) and by re-fetching the fixed banner URL, which `xmllint` now confirms is well-formed.
- All GitHub stats/streak/top-langs images reference `username=AhsanBilal7` — update if the handle changes.
- Contact links, CV, and Google Scholar / ORCID / DBLP / Semantic Scholar IDs are pulled from [ahsanbilal7.github.io](https://ahsanbilal7.github.io/); update both places together if any of these change.
- Publications (title, authors + their personal-site/Scholar links, venue, status, arXiv PDF) are sourced verbatim from the publications data on ahsanbilal7.github.io. 16 of 20+ papers are shown grouped by research area (LLM Reasoning/Agentic AI/RL vs. Wireless/Signal/Generative ML); the remaining 4 early-career/under-review items sit in a collapsed "Additional work" section (a numbered list in the Research design). Full live list is linked via Google Scholar in each design.
- Designs 1–3, 5 and 6 use a `<picture>` element with `prefers-color-scheme` sources on their GitHub Stats/Top-Langs/Streak images so they render correctly in both light and dark GitHub viewer themes. Design 4 (Retro) is intentionally a single committed dark terminal look, with a light-mode `<picture>` source only for the stats card so it never appears unreadable on a white background.
- **Design 6 (Visual)** references `assets/visuals/*.svg` — four hand-authored, self-contained SMIL-animated SVGs (optimization descent, test-time reasoning search, RL agent–environment loop, diffusion denoising) with built-in `prefers-color-scheme` styling — via `raw.githubusercontent.com/AhsanBilal7/AhsanBilal7/main/...` so the images resolve correctly whether viewed from `designs/` or after copying to the root README. **This requires `assets/visuals/` to be pushed to the `main` branch** before those four images will load.

## Root cause: the `xmlParseEntityRef: no name` error

If an image stops rendering and a browser shows *"This page contains the following errors: error on line N at column M: xmlParseEntityRef: no name"* — that's Firefox's raw-XML parser choking on a malformed SVG returned by an external badge/banner service (capsule-render, readme-typing-svg, etc.). Root cause: those services interpolate the `lines=`/`desc=`/`text=` query text directly into the SVG's `<text>` nodes without re-escaping `&` back to `&amp;`. If your query string contains a literal `&` (even percent-encoded as `%26`, since it's decoded server-side before being embedded), the service emits invalid XML. Fix: never put a raw `&` in those params — use `·`, "and", or restructure the phrase instead.
