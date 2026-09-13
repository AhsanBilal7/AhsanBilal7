# Profile README — Design Variants

Three complete, self-contained designs for the `AhsanBilal7/AhsanBilal7` profile README. Every variant carries the **same information** (research focus, who-I-am, current work, contributions/service, selected publications, honors, toolbox, GitHub stats, and contact links) — only the visual style differs. Pick one and copy its content into the root `README.md`.

| # | File | Style | Palette |
|---|---|---|---|
| 1 | [`../README.md`](../README.md) *(live)* | **Signal** — clean academic-minimal, centered hero, tables | Blue `#2563EB` |
| 2 | [`design-terminal.md`](./design-terminal.md) | **Terminal** — dev/monospace, code-block sections, dark badges | Slate + Electric blue `#0D1117` / `#58A6FF` |
| 3 | [`design-cards.md`](./design-cards.md) | **Cards** — Nord-inspired grid/table layout, collapsible toolbox | Nord `#3B4252` / `#88C0D0` / `#5E81AC` |

## How to switch the live design

```bash
cp designs/design-terminal.md README.md   # or design-cards.md
git add README.md
git commit -m "Switch profile README design"
```

## Notes

- All GitHub stats/streak/activity-graph images reference `username=AhsanBilal7` — update if the handle changes.
- Contact links, CV, and Google Scholar / ORCID / DBLP / Semantic Scholar IDs are pulled from [ahsanbilal7.github.io](https://ahsanbilal7.github.io/); update both places together if any of these change.
- Publications (title, authors + their personal-site/Scholar links, venue, status, arXiv PDF) are sourced verbatim from the publications data on ahsanbilal7.github.io. 16 of 20+ papers are shown grouped by research area (LLM Reasoning/Agentic AI/RL vs. Wireless/Signal/Generative ML); the remaining 4 early-career/under-review items sit in a collapsed "Additional work" section. Full live list is linked via Google Scholar in each design.
- All three designs' GitHub Stats/Streak/Top-Langs/Activity-Graph images use a `<picture>` element with `prefers-color-scheme` sources so they render correctly in both GitHub's light and dark viewer themes.
