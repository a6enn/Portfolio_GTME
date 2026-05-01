# portfolio/

Public-facing site. Single-folder, no build step. Open `index.html` in a browser.

## Entry point

**`index.html`** — start here. Hero, About, Skills, Career, Writing, Projects, Contact. Every other HTML file in this folder is reached from here.

## Pages linked from `index.html`

| File | Section on index | What it is |
|---|---|---|
| `prospecting.html` | Projects (featured) | Arteria production prospecting workflow |
| `clay-private-equity.html` | Projects | Clay GTM engineering case study (PE sourcing) |
| `highbeam-signals.html` | Projects | Signal stack for a consumer fintech |
| `skill-architecture.html` | Writing (featured) | Essay — modular vs. monolithic skills |
| `model-selection.html` | Writing | Essay — picking the right model for the task |
| `post-meeting-tax.html` | Writing | Essay — post-meeting workflow as a systems problem |

## Other files

| File | Purpose |
|---|---|
| `CLAUDE.md` | Context layer for Claude — design system, voice, file map. Not part of the site. |
| `README.md` | This file. Not part of the site. |
| `_archive/` | Old assets kept for reference. Not part of the site. |

## How to view

```bash
# Easiest — open in default browser
open index.html

# Or run a local server
cd ~/Desktop/Claude_Projects/portfolio
python3 -m http.server 8000
# then open http://localhost:8000
```

## Conventions

- One HTML file per page. Inline CSS and JS. No external build.
- Shared design system: Instrument Serif (display) + Inter (body), warm off-white `#f5f2eb`, green primary `#135b45`.
- All cross-page links use relative paths (`index.html`, `index.html#projects`, etc.).

*Last cleaned: April 2026*
