# Daily Work Log — ES ENERGOSERVIS

Interactive **daily work log** (evidencija rada) for ES ENERGOSERVIS.
Opens in any browser (phones included), is filled in with a few taps, and prints to a clean **A4 PDF**.

## 🔗 Live link
**https://labranka.github.io/evidencija-rada/**

## Features
- Pick the work site per worker with one tap: **Vršac / Sremska Rača / Radionica (Workshop)**
- Hours are calculated automatically from the start and end time
- In-field signature (finger on a phone, mouse on desktop) and a description of the work performed
- **Add and remove** workers (rows) with a click
- Breakdown per work site plus total hours (also printed in the PDF)
- **Sačuvaj** (Save, locally on the device) and **Štampaj / PDF** (Print / PDF, A4)

## How to use
1. Open the link.
2. Check the date and enter the person in charge (supervisor).
3. For each worker choose the work site, enter the start and end time, and sign.
4. Describe the work performed at the bottom.
5. **Sačuvaj** (Save), then **Štampaj / PDF → "Save as PDF"**.

> Entered data stays **locally in the browser** (localStorage) and is never sent anywhere.
> The permanent copy is the PDF you create yourself.
> When printing, turn off "Headers and footers" in the print dialog
> so the date and URL the browser adds on its own disappear.

## Files
- `index.html` — the interactive log: a single self-contained HTML file (vanilla JS, CSS print styles, canvas signature pad). No build step, no backend.
- `evidencija-rucni-template.html` / `Evidencija-rada-RUCNI-template.pdf` — a blank version of the same form for printing and filling in by hand.
- `wrangler.toml` — Cloudflare static-assets config, an alternative host to GitHub Pages.
