# India Rainfall Dashboard

Interactive dashboard analysing **115 years of Indian rainfall (1901–2015)** with historical trends, seasonality, regional comparisons, district normals, and a 2016 forecast view.

## Highlights

- Explore annual rainfall from 1901 to 2015.
- Compare 36 meteorological subdivisions and 641 districts.
- Filter by historical epoch, year range, season, and month.
- Review KPI cards, trends, seasonal patterns, and forecast insights.
- Use the dashboard directly in a modern browser with no build step.

## Run locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/Puneet2999/india-rainfall-dashboard.git
cd india-rainfall-dashboard
# Open index.html in your browser
```

The dashboard loads Plotly and Tailwind CSS from their CDNs. The bundled `dashboard_data.js` file contains the pre-processed data used by the interface.

## Repository contents

- `index.html` — dashboard interface and visualizations
- `dashboard_data.js` — pre-processed rainfall data
- `LICENSE` — MIT license

## Data scope

The dashboard covers historical Indian rainfall records from 1901 through 2015. Forecast values are presented as an exploratory view and should not be treated as operational meteorological guidance.
