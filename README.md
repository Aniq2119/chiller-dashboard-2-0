# Chiller Monitoring Dashboard 2.0

Live demo: https://<your-username>.github.io/chiller-dashboard-2-0/

## What this shows
- Total cooling load (RT), per-chiller loads and power (kW), and plant efficiency (kW/RT).
- Animated comparison between default vs GA-BMO power profiles.
- A published “Cooling Demand Table” for reproducibility.

## Data sources
- This page reads from published Google Sheets CSV endpoints (read-only).
- Update interval: 30 s (plant metrics), 60 s (demand table).

## How to reproduce
1. Publish your Google Sheet to the web (File → Share → **Publish to the web** → CSV).
2. Replace the CSV URLs in `index.html`.
3. Commit to `main`. GitHub Pages deploys automatically.

## Notes
- No backend required; static hosting on GitHub Pages.
- If a chart/table is blank, verify the CSV links are public and published.
