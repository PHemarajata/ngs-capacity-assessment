# NGS Capacity Assessment — APHL Global Health

A self-administered assessment of laboratory capacity for next-generation sequencing and bioinformatics, used by APHL partner laboratories.

The assessments are static HTML — no backend, no build step. Answers save to the browser's localStorage on the device they're filled out on.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Landing page linking to the forms |
| `NGS Assessment Full Baseline - APHL v6.html` | **Latest full assessment** (recommended) |
| `NGS Assessment Full Baseline - APHL v6-print.html` | Print-optimized layout of the same form |
| `NGS Assessment Full Baseline - APHL v6 (standalone).html` | Single-file offline version of the full assessment (all assets inlined) |
| `NGS Assessment Short Form - APHL v2 (standalone).html` | **Latest short form** — condensed periodic check-in |
| `Short Form User Guide.html` | How-to guide for the short form |
| `tweaks-panel.jsx` | Helper component referenced by the user guide |
| `assets/` | Logo and lab photography used by the non-standalone files |

## Hosting with GitHub Pages

1. Push this folder to a new repository (drag-drop the folder contents into GitHub's web "Add file → Upload files" works fine).
2. In the repo: **Settings → Pages**.
3. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. After a minute your forms are live at `https://<user>.github.io/<repo>/`.

The Pages URL handles iPad correctly — open it in Safari, the form runs, answers save. To keep it one tap away on iPad: Share → Add to Home Screen.

## Local use

Open `index.html` in any modern browser. The standalone `(standalone).html` files work even with no internet — every asset (fonts, images, JS, CSS) is inlined.

## Notes for iPad users

- **Don't** open AirDropped HTML files from Files / Quick Look — that previewer disables JavaScript and the form won't load.
- **Do** open the hosted URL in Safari, or use a browser app like Documents by Readdle that runs scripts on local files.
- Answers are stored per-browser, per-origin. Switching devices or browsers starts a fresh form. Use the form's built-in export / save before closing the tab if you need a transferable record.

## Contact

Peera Hemarajata, M.D., Ph.D. · APHL Global Health · `peera.hemarajata@tha.aphl.org`
