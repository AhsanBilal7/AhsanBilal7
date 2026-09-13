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
- **Whoami / keywords / venues are prominent, above the fold, in every design.** Directly under the name: a one-line identity/whoami, a research-keywords badge row (LLM Reasoning, Test-Time Compute, Agentic AI, RL, Diffusion Models, Wireless ML), and a "Publishes In" venue row (ICML, NeurIPS, COLM, KDD, TMLR, AAAI, ICASSP, ICC) — before Current Work or Publications.
- **SVG entity bug, fixed:** capsule-render and readme-typing-svg do not XML-escape a raw `&` placed in `desc=`/`lines=`/`text=` params, which corrupts the returned SVG's XML (`xmlParseEntityRef: no name`) and breaks the image in strict renderers. All six designs now use `·` (or restructured text) instead of `&` in every such parameter — verified with `grep -rn '%26'` across all files (no matches).
- All GitHub stats/streak/top-langs images reference `username=AhsanBilal7` — update if the handle changes.
- Contact links, CV, and Google Scholar / ORCID / DBLP / Semantic Scholar IDs are pulled from [ahsanbilal7.github.io](https://ahsanbilal7.github.io/); update both places together if any of these change.
- Publications (title, authors + their personal-site/Scholar links, venue, status, arXiv PDF) are sourced verbatim from the publications data on ahsanbilal7.github.io. 16 of 20+ papers are shown grouped by research area (LLM Reasoning/Agentic AI/RL vs. Wireless/Signal/Generative ML); the remaining 4 early-career/under-review items sit in a collapsed "Additional work" section (a numbered list in the Research design). Full live list is linked via Google Scholar in each design.
- Designs 1–3, 5 and 6 use a `<picture>` element with `prefers-color-scheme` sources on their GitHub Stats/Top-Langs/Streak images so they render correctly in both light and dark GitHub viewer themes. Design 4 (Retro) is intentionally a single committed dark terminal look, with a light-mode `<picture>` source only for the stats card so it never appears unreadable on a white background.
- **Design 6 (Visual)** references `assets/visuals/*.svg` — four hand-authored, self-contained SMIL-animated SVGs (optimization descent, test-time reasoning search, RL agent–environment loop, diffusion denoising) with built-in `prefers-color-scheme` styling — via `raw.githubusercontent.com/AhsanBilal7/AhsanBilal7/main/...` so the images resolve correctly whether viewed from `designs/` or after copying to the root README. **This requires `assets/visuals/` to be pushed to the `main` branch** before those four images will load.

## Root cause: the `xmlParseEntityRef: no name` error

If an image stops rendering and a browser shows *"This page contains the following errors: error on line N at column M: xmlParseEntityRef: no name"* — that's Firefox's raw-XML parser choking on a malformed SVG returned by an external badge/banner service (capsule-render, readme-typing-svg, etc.). Root cause: those services interpolate the `lines=`/`desc=`/`text=` query text directly into the SVG's `<text>` nodes without re-escaping `&` back to `&amp;`. If your query string contains a literal `&` (even percent-encoded as `%26`, since it's decoded server-side before being embedded), the service emits invalid XML. Fix: never put a raw `&` in those params — use `·`, "and", or restructure the phrase instead.
