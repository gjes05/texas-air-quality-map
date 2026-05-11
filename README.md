Texas Air Quality Monitor 🌍

An interactive GIS map visualizing real-time air quality index (AQI) data across Texas, built with the ArcGIS Python API and live data from the World Air Quality Index (WAQI) API.

## Features
- Live AQI data fetched from WAQI API across 31 monitoring stations in Texas
- Color-coded markers by AQI category:
  - 🟢 Green — Good (0-50)
  - 🟡 Yellow — Moderate (51-100)
  - 🔴 Red — Unhealthy (100+)
- Interactive map powered by ArcGIS with zoom and pan
- Coverage across major Texas cities: Houston, Dallas, Austin, San Antonio, El Paso, and more

## Tech Stack
- Python 3
- ArcGIS Python API (`arcgis` 2.4.3)
- WAQI Air Quality API
- Pandas
- Jupyter Notebook

## Setup
```bash
pip install arcgis arcgis-mapping pandas requests
```

1. Get a free WAQI API token at https://aqicn.org/data-platform/token/
2. Get a free ArcGIS Developer account at https://developers.arcgis.com
3. Add your tokens to the notebook
4. Run all cells

## Data Source
Live air quality data from the [World Air Quality Index Project](https://waqi.info), 
covering EPA-monitored stations across Texas.

## Preview
Open `texas_air_quality_map.html` in your browser for a live interactive demo.
