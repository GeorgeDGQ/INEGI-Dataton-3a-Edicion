# CDMX 2029: Elderly Care & Demographic Analysis

An interactive geospatial and demographic platform developed for the **INEGI Datathon (3rd ed.)** in partnership with EPIC Lab ITAM. It evaluates the growing gap between elderly population growth and formal nursing home capacity across Mexico City's 16 boroughs.

---

## Methodology

* **Demographic Projections:** Ensemble model averaging historic linear regression (2000–2020 censuses) and cohort-component survival methods (7.63% backtest error against 2020).
* **Territorial Clustering:** $K$-means clustering ($k=3$) factoring normalized projected demand, public care supply, and household income to classify borough-level investment priority.
* **Urban Environment:** Crime heatmaps and borough rates (per 10k residents) cross-referenced with public/private care facilities.

---

## Data Sources & Tech Stack

* **Data:** INEGI (Censuses 2000–2020, DENUE, ENIGH) & CDMX Open Data (Crime records)[cite: 2].
* **Stack:** Python (Pandas, GeoPandas), HTML5/CSS3, JavaScript (Leaflet.js, Leaflet.heat, Chart.js)[cite: 2].
