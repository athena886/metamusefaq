# 9/10 polish

2026-10-30 — hero panel, capability grid, jump chips, FAQ/Related; tokens unchanged.

- Added an ink M tile with a teal corner, a tighter wordmark, and a quiet teal period.
- Wrapped existing hero content in a white panel with a 4% teal top wash. Hero ledes use their existing first sentence and clamp at two visual lines; remaining sentences remain verbatim below the panel.
- All hero Checked chips share the existing homepage/site review date, 2026-10-30, through `LATEST_REVIEW_DATE`. Existing source-review dates in article bodies are unchanged.
- Added five homepage jump links to existing heading anchors, a two-column capability grid (one column on mobile), and teal-bar business/pricing callouts.
- Added short section rules, subtle table striping, a stronger Power card border, equal-height pricing cards, larger FAQ targets with an open-state wash, two-column related cards with clamped descriptions, and a teal footer hairline.
- Hover transitions are limited to 120ms; reduced-motion preferences disable transitions and movement.

Verification: build and diff checks pass. All five requested pages were checked at 390px and 1280px without document-level horizontal overflow. Checked chip confirmed on pricing; FAQ open-state background is #E7F5F3 with 20px summary vertical padding. All existing article words, H1 text, prices, article hrefs, metadata and JSON-LD were preserved against the pre-polish build (new status/jump chrome excluded). Shared CSS contains none of the banned warm tokens. Teal on white remains 5.47:1 contrast; ink on background remains 16.82:1.

Local preview: http://127.0.0.1:4323/. No commit, push, deployment, DNS change, or secret change.
