# Sgorio — Tabl 16 / League Table Builder

A single-page web app for building the Sgorio 16-team league table and
exporting it as JSON for DataClay.

**Live app:** https://creadigol-design.github.io/sgoriorebrand/

## Use it

Open the live link above (or `docs/index.html` locally in any browser).
For each of the 16 positions set the movement indicator (▲ up / ▼ down /
— same), pick the club, and type the stats, then click **Allforio JSON /
Export JSON** to download a DataClay-ready file.

The export is an array containing one object with 128 position-prefixed
string keys (`1Standing`, `1ClubName`, … `16Points`).

## Hosting

GitHub Pages serves `docs/index.html` from the `main` branch
(Settings → Pages → Deploy from a branch → `main` → `/docs`). Any push to
`main` republishes the site automatically.
