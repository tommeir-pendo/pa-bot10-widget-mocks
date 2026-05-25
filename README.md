# PA-bot10 widget mocks

Standalone Highcharts HTML mocks hosted via GitHub Pages so they can be embedded in Pendo IFrame Code Widgets on dashboard `e-hF44V9HygyjIxhxrlL8MGvSoY`.

Source of truth: `pendo-io/dozer` (private) — `prototypes/deal-desk-custom-widget-exploration-2026-05-25/`.

This repo exists only because:
- Pendo's `htmlEmbed` widget needs a public URL with `Content-Type: text/html` and executable inline scripts.
- jsDelivr, gist.githack, rawgit, combinatronics either don't serve gists or are defunct.
- htmlpreview.github.io is a JS-shim — Highcharts doesn't load reliably inside Pendo's sandboxed iframe.

Update flow: edit upstream in dozer → copy here → commit → push → GitHub Pages serves at `https://tommeir-pendo.github.io/pa-bot10-widget-mocks/<file>.html`.
