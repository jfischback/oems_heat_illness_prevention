# OEMS Heat Stress Screening

Static page (no build step). Toggle between:

- **NIOSH** (DHHS (NIOSH) Publication 2016-106): RAL = 59.9 − 14.1 log10 M and REL = 56.7 − 11.5 log10 M (°C-WBGT, M in watts), using 1-hour TWA WBGT and metabolic rate with work/rest.
- **OSHA (proposed)** 29 CFR 1910.148 (proposed Aug 30, 2024; not final): initial trigger = heat index 80 °F or WBGT equal to the NIOSH RAL; high trigger = heat index 90 °F or WBGT equal to the NIOSH REL. Heat index uses the National Weather Service equation.

Files: `index.html` (page), `heat-calc.js` (math), `heat-app.js` (page logic), `heat.css`, `style.css`, `disclaimer.js/.css`.

Tests: `node tests/check.mjs`
