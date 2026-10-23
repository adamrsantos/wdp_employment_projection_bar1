# Fast Growth Industries Chart

This project displays a side-by-side set of Highcharts bar charts using the data in `data_53.csv`.

## Files

- `index.html` — page layout and chart bootstrap
- `side_by_side_bar.js` — CSV parsing and chart rendering logic
- `data_53.csv` — source data for the graphs

## Local preview

Run a static server from the project directory:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## GitHub Pages

This repository is configured for GitHub Pages deployment using a GitHub Actions workflow in `.github/workflows/deploy-pages.yml`.

After pushing to GitHub, enable Pages in the repository settings with the source set to "GitHub Actions".
