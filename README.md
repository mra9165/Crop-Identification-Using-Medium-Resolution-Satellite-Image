# 🌾 Crop Identification Using Medium-Resolution Satellite Imagery

## 📍 Study Area
- **Location:** Badigwa Village, Karnataka, India

## 🛰️ Platform & Data
- **Platform:** Google Earth Engine (GEE)
- **Satellite Data:** Sentinel-2 (Medium Resolution)
- **Spatial Resolution:** 10–20 m
- **Temporal Data:** Multi-date time series

## 🎯 Project Objective
To identify and classify crop types using time-series vegetation indices and a Random Forest classifier implemented in Google Earth Engine.

## 🌱 Vegetation Indices Used
- **NDVI (Normalized Difference Vegetation Index)**
- **OSAVI (Optimized Soil Adjusted Vegetation Index)**
- **RVI (Ratio Vegetation Index)**

## ⏱️ Feature Engineering
- Computation of NDVI, OSAVI, and RVI for multiple dates
- Temporal stacking of vegetation indices
- Time-series feature stack captures crop phenological patterns

## 🤖 Classification Model
- **Algorithm:** Random Forest
- **Input Features:**
  - Time-series NDVI
  - Time-series OSAVI
  - Time-series RVI
- **Training Data:** Ground truth crop samples

## 🔬 Methodology
1. Define Area of Interest (Badigwa village)
2. Load Sentinel-2 imagery in GEE
3. Apply cloud masking and preprocessing
4. Compute NDVI, OSAVI, and RVI
5. Create time-series feature stacks
6. Train Random Forest classifier
7. Perform crop classification
8. Validate results

## 📊 Output
- Crop classification map
- Feature importance analysis
- Accuracy assessment

## 🛠️ Tools & Technologies
- Google Earth Engine (JavaScript API)
- Sentinel-2 MSI
- Random Forest Classifier
- Remote Sensing & GIS

## 🌾 Applications
- Crop mapping
- Precision agriculture
- Agricultural monitoring
- Decision support systems

## 🔮 Future Scope
- Integration of Sentinel-1 SAR data
- Deep learning-based crop classification
- Multi-season and multi-year analysis

## 🙏 Acknowledgements
- Google Earth Engine
- European Space Agency (ESA)


