# indiaaqi

An interactive AQI mapping project built using real-time PM10 data across Indian cities (2023–2025).  
The goal was to convert raw pollutant readings into something visual, usable and insightful.

# What’s Inside

This project:
- Builds an interactive AQI map using Plotly + Mapbox
- Lets you **filter by AQI categories** (Good, Moderate, Poor, etc.)
- Shows tooltips with city, AQI, station, PM10 — all in one clean hover box
- Generates **3 key graphs** to break down trends:
  - Top 10 Most Polluted Cities
  - AQI Category Distribution
  - State-wise AQI Comparison

All of this is done using the PM10 values from real-time datasets.

---

# Files

| File | Purpose |
|------|---------|
| `AQI.csv` | Raw dataset (with PM10, PM2.5, etc.) |
| `realtime_india_aqi.csv` | Cleaned dataset used for mapping |
| `AQI.ipynb` | Notebook with full code (cleaning, map, graphs) |
| `aqi_map.html` | Interactive AQI map (open in browser) |
| `top10_polluted_cities.png` | Bar chart – worst air quality cities |
| `statewise_aqi.png` | Bar chart – state-level avg AQI |
| `aqi_category_distribution.png` | AQI category count across stations |

---

# Tech Used

- Python (Pandas, Plotly, Seaborn, Matplotlib)
- Real-time dataset from [Kaggle](https://www.kaggle.com/datasets/ishankat/real-time-air-quality-index-aqi-india-20232025)
- Map rendered using Plotly’s `scatter_mapbox`

---

# Final Words

The whole point was to turn boring pollutant numbers into something people can see and understand — in a single click.  


