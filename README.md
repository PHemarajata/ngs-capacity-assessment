# Pathogen Genomic Surveillance Capacity Assessment | APHL Global Health

This repository hosts the public web page for the assessment forms: https://phemarajata.github.io/ngs-capacity-assessment/

The forms assess public health laboratory capacity for pathogen genomic surveillance. Each is a single, self-contained HTML file with no backend and no build step. Answers save to the browser's localStorage on the device they're filled out on.

The source of record, with the overview, release notes, version history and printable covers, is [PHemarajata/pathogen-genomics-capacity-assessment](https://github.com/PHemarajata/pathogen-genomics-capacity-assessment). New releases are made there first and copied here.

## Current forms

| File | Form | Build |
|------|------|-------|
| `instruments/NGS_Assessment_Short_Form_-_APHL_v4.1__standalone_.html` | Short Form v4.1, sent to each laboratory before the visit | 2026-11-12a |
| `instruments/NGS_Assessment_Full_Baseline_-_APHL_v8.1__standalone_.html` | Full Baseline v8.1, completed on site for each laboratory | 2026-11-12a |
| `instruments/NGS_Assessment_Leadership_Annex_-_APHL_v1.1__standalone_.html` | Enabling Environment Annex v1.1, completed once for each site | 2026-11-16a |

## Other files

| File | Purpose |
|------|---------|
| `index.html` | Landing page linking to the forms |
| `NGS Assessment Full Baseline - APHL v6.html`, `-print.html`, `(standalone).html` | Full Baseline v6, kept so that links already shared keep working |
| `NGS Assessment Short Form - APHL v2 (standalone).html` | Short Form v2, kept for the same reason |
| `Short Form User Guide.html`, `tweaks-panel.jsx` | User guide for Short Form v2 and the helper it loads |
| `assets/` | Logo and photography used by the landing page and the v6 files |

## Hosting

GitHub Pages serves this repository from branch `main`, folder `/ (root)`.

## Local use

Open `index.html` in any modern browser. The forms in `instruments/` work with no internet, because every asset is inlined.

## Notes for iPad users

- **Don't** open AirDropped HTML files from Files or Quick Look. That previewer disables JavaScript and the form won't load.
- **Do** open the hosted URL in Safari, or use a browser app like Documents by Readdle that runs scripts on local files.
- Answers are stored per browser and per site. Switching devices or browsers starts a fresh form. Use the form's export before closing the tab if you need a record you can move.

## Contact

Peera Hemarajata, M.D., Ph.D. · APHL Global Health · `peera.hemarajata@tha.aphl.org`
