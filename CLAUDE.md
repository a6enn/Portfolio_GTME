# Portfolio — Project Briefing

*Read this first when working in this folder.*

---

## What This Folder Is

Adam's public-facing portfolio. Two HTML pages: a personal site and a prospecting workflow demo. Both are self-contained single-file HTML — no build step, no dependencies except Google Fonts.

The portfolio exists to make the thinking visible. Alpha Forge posts are the content layer; the prospecting demo is a live artifact of the GTM stack. Both should stay current as the underlying work evolves.

## Current Status (April 2026)

Both pages are live and functional. No active development in progress.

## Folder Structure

```
portfolio/
├── CLAUDE.md          ← You are here
├── index.html         ← Main personal portfolio (Adam Genn — GTM & Solutions Engineering)
└── prospecting.html   ← AI Prospecting Workflow demo page
```

## Design System

Both pages share the same design language. Do not deviate from it when making edits.

- **Fonts:** Instrument Serif (headings, display), Inter (body)
- **Colors:** `--bg: #f5f2eb` (warm off-white), `--green: #135b45` (primary), `--text: #151515`, `--muted: #737373`
- **Style:** Minimal. No heavy decoration. Content-first.

## How This Folder Connects to Others

**Alpha Forge → portfolio:** Posts from Alpha Forge are the content layer of this site. When new posts ship and are worth featuring, `index.html` should be updated to reflect them.

**Prospecting → portfolio:** `prospecting.html` is a demo of the GTM stack built in the Prospecting folder. As that stack evolves (new ICP logic, new outreach patterns, new proof points), the demo page should reflect it.

## How to Update This File

Update this CLAUDE.md when:
- A new page is added to the portfolio
- The design system changes
- The portfolio's purpose or audience shifts
- Development becomes active again after a dormant period

---

*Last updated: April 2026*
