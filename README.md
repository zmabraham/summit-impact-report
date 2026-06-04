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

## Live pages

GitHub Pages serves `index.html` from the repo root.
The redesigned version is at `/jsicp-2026-impact-report.html`.

## Local preview

```sh
python -m http.server 8000
# open http://localhost:8000
```
