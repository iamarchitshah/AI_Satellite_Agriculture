# 🌾 AI-Powered Satellite Image Analyzer for Agriculture

This project leverages satellite imagery and artificial intelligence to empower modern precision agriculture. It helps detect crop stress, predict yield, and recommend interventions using deep learning models and remote sensing data — all visualized through an interactive Streamlit dashboard.

---

## 🧠 Project Objective

- Detect crop health using NDVI and CNN segmentation
- Predict crop yield using time-series NDVI and LSTM
- Enable real-time insights using Google Earth Engine
- Provide farmer-focused suggestions (water, fertilizer)

---

## 🧩 Key Features

### 🛰️ 1. Crop Health Analyzer
- Upload NDVI `.tif` satellite images (e.g., Sentinel-2)
- Processes image using a trained **U-Net** segmentation model
- Highlights healthy vs. unhealthy crop regions
- Visual overlay of segmented crop stress areas

### 📈 2. Yield Predictor (CSV Upload)
- Upload NDVI time series data (`.csv` with NDVI values)
- Forecast crop yield in tons/hectare
- Uses LSTM (Long Short-Term Memory) model for prediction
- Chart to visualize NDVI over time

### 🌍 3. Yield Predictor (Map Auto-Fetch)
- Click any location on the world map
- NDVI time series is auto-fetched using **Google Earth Engine**
- Select start and end date range
- Instantly visualize NDVI trends and get yield prediction

---

## 🖥️ UI Dashboard

- Built using **Streamlit**
- Responsive tabs for different modules
- Real-time NDVI visualization
- Prediction overlays + exportable insights

---

## 🧰 Tech Stack

| Layer            | Tools/Tech                                   |
|------------------|----------------------------------------------|
| 🌐 Satellite Data | Google Earth Engine, Sentinel-2, Landsat     |
| 🧠 Models         | TensorFlow/Keras (U-Net, LSTM)               |
| 🖼️ Image Processing | OpenCV, Rasterio, GDAL, NumPy                 |
| 🌱 Visualization  | Streamlit, Folium, Matplotlib, Leaflet.js   |
| ☁️ Storage        | Firebase / AWS S3 / Local                    |
| 🧪 Language        | Python                                       |

---
