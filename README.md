# Urban Heat & Livability Analysis — India (2015–2024)

A comparative data analysis of urban heat island intensity, vegetation 
cover, air quality, and livability trends across 5 major Indian metro 
cities using satellite remote sensing and ground-based AQI data.

## Cities Analyzed
Hyderabad | Delhi | Mumbai | Bengaluru | Chennai

## Data Sources
- **Land Surface Temperature & NDVI** — Landsat 8 Collection 2 (Google Earth Engine)
- **Air Quality Index (AQI)** — CPCB via Kaggle + UrbanEmissions.info (2015–2023)
- **Population** — Census of India 2001, 2011 (interpolated to yearly estimates)

## Key Findings
- **Bengaluru** is the fastest warming city (+3.58°C, 2015–2024) driven 
  by the steepest green cover loss (-0.035 NDVI)
- **Delhi** has the worst air quality (avg AQI 237) but showed the 
  strongest improvement (-31.4% AQI drop, 2015–2023)
- **Chennai** achieved the best heat-pollution decoupling — AQI fell 
  -47.4% with near-zero temperature change
- **Mumbai** is the only city worsening on both heat (+5.9%) and 
  air quality (+8.7%) simultaneously
- 4 of 5 cities successfully decoupled air quality improvement from 
  urban heat — a key policy finding

## Original Metrics Developed
- **Heat Sensitivity Coefficient** — °C rise per 0.01 NDVI drop (city-specific)
- **Livability Trajectory Classification** — 2×2 quadrant system based 
  on LST and AQI trend directions
- **Heat-Pollution Decoupling Index** — indexed comparison of relative 
  LST vs AQI change from baseline year

## Project Structure
