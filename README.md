# JSICP '26 Summit — Impact Report

Static impact-report site for the Jewish Spirituality in Clinical Practice
Inaugural Summit 2026, re-skinned to the JSICP '26 brand (teal monochrome,
topographic pattern, Sharp Slab / Acumin / Founders Grotesk).

Built from a Claude Design handoff bundle. See `index.html` for the page;
`summit-impact-report-standalone.html` is the single-file bundle with every
asset inlined (~5 MB) and works fully offline.

`jsicp-2026-impact-report.html` is a second, fully redesigned version from a
later Claude Design handoff (light-dominant teal bands, interactive maps with
per-region registrant tooltips, segmented disciplines ring, NPS gauge). It
uses `report.css` plus the shared `colors_and_type.css`, fonts, and assets.

`jsicp-2026-impact-report-v2.html` is the v2 content restructure of that
redesign (sections trimmed and reordered, tiered testimonials, 11 countries
incl. South Africa, +60 NPS stat card). It uses its own `report-v2.css` so
the v1 page's styling stays frozen.

## Live pages

GitHub Pages serves `index.html` from the repo root.
The redesigned version is at `/jsicp-2026-impact-report.html`.
The v2 restructure is at `/jsicp-2026-impact-report-v2.html`.

## Local preview

```sh
python -m http.server 8000
# open http://localhost:8000
```
