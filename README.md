# 🌍 Smart Urban Heat Mapping
A full-stack web application that analyzes and predicts Urban Heat Islands (UHI) across Indian cities using satellite imagery, weather data, and machine learning.

## Problem
Urban areas often experience higher temperatures than surrounding regions due to reduced vegetation and increasing built-up areas.
This project helps visualize heat distribution and predicts heat risk using satellite-derived environmental indicators.

## Features
- Live city heat analysis
- Google Earth Engine satellite integration
- NDVI, NDBI, NDWI & Albedo calculation
- Weather API integration
- Machine Learning heat risk prediction
- Interactive heat maps
- Historical trend analysis

## Tech Stack ##
### Backend
- Python
- FastAPI
- Uvicorn
### Frontend
- React
- Streamlit
### Machine Learning
- Scikit-learn
- Random Forest
### GIS
- Google Earth Engine
- Rasterio
- GeoPandas
- Folium
### Database
- SQLite
- 
## System Architecture

```
User
   │
React / Streamlit
   │
FastAPI
   │
Data Pipeline
   ├── Google Earth Engine
   ├── OpenWeather API
   └── Geocoding API
   │
Feature Engineering
   │
Random Forest Model
   │
Heat Risk Prediction
```

---

## Machine Learning Pipeline

```
Satellite Images
        │
Feature Extraction
        │
 NDVI
 NDBI
 NDWI
 Albedo
 LST
 Weather
        │
Feature Engineering
        │
Random Forest Regressor
        │
Heat Risk Score
```

## Project Structure

```
backend/
frontend/
scripts/
models/
data/
```

## Key Challenges Solved

✔ Integrated multiple satellite datasets using Google Earth Engine

✔ Built an automated pipeline for feature extraction

✔ Combined weather APIs with remote sensing data

✔ Developed a machine learning model for heat prediction

✔ Visualized geospatial insights using interactive maps

## Screenshot
<img width="1920" height="1128" alt="Screenshot 2025-10-11 160914" src="https://github.com/user-attachments/assets/617d42bd-e89e-49fa-aefe-9714cd2ee47e" />


## Future Improvements

- Deep Learning models
- Real-time monitoring
- Mobile application
- Heatwave alert system
