# 🛰️Monitoring Soil Degradation with Remote Sensing

## 🌍Overview
A comprehensive analysis of soil degradation in Karnataka, India (2015-2019) using remote sensing techniques and Google Earth Engine. The project implements three different change detection methods to assess and visualize land degradation patterns, achieving up to 76.3% accuracy.

## 📊Methods
1. **Index Differencing**
   - NDVI (Normalized Difference Vegetation Index)
   - BI (Bare Soil Index)

2. **Change Vector Analysis**
   - Using NIR, SWIR, and Red bands
   - Analysis of magnitude (rho) and direction (alpha) of change

3. 🗺**RUSLE with Ancillary Data**
   - Rainfall erosivity factor (R)
   - Soil erodibility factor (K)
   - Slope length and steepness factor (LS)
   - Cover management factor (C)
   - Conservation practice factor (P)

## 📈Results
- Index Differencing: 60.3% accuracy with BI
- Change Vector Analysis: 50.05% accuracy
- RUSLE with Ancillary Data: 76.3% accuracy

## 🛠️Tech Stack
- Google Earth Engine
- Remote Sensing
- RUSLE (Revised Universal Soil Loss Equation)
- Change Detection Analysis

## 📚Data Sources
- USGS Landsat 8 Level 2
- MODIS Land Cover
- CHIRPS Dataset
- OpenLandMap
- WWF HydroSHEDS
