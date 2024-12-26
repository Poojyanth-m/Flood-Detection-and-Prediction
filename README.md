---

# 🌊 Flood Detection and Prediction

A project focused on detecting and predicting flood events using satellite data, machine learning models, and environmental monitoring techniques. The system aims to assist in early flood warnings and disaster management.

---

## Features ✨

- **Flood Detection**: Utilize satellite imagery and environmental data to detect potential flood-prone areas.
- **Prediction Model**: Leverage machine learning models to predict future flood events based on historical data.
- **Real-time Monitoring**: Monitor flood levels and predict their impact using satellite data and geographical parameters.
- **Data Visualization**: Visualize flood-prone areas and predictive results on a user-friendly interface.
- **Environmental Data Integration**: Integrate climate and environmental data to enhance flood prediction accuracy.

---

## How it Works ⚙️

1. **Data Collection**: Satellite data and environmental parameters are collected from relevant sources.
2. **Flood Detection**: Machine learning algorithms analyze the data to detect flood-prone regions.
3. **Flood Prediction**: A prediction model estimates the likelihood and intensity of potential flood events.
4. **Visualization**: Interactive maps and graphs visualize the flood detection and prediction results.
5. **Real-time Updates**: The system offers real-time alerts based on predictions and detected anomalies.

---

## Models Used 🧠

- **YOLOv5**: Used for detecting flood-affected areas and identifying objects within satellite images. YOLOv5 helps in real-time detection and localization of flood events.
  
- **Mask RNN**: A model employed for segmentation tasks, focusing on detecting and delineating flooded regions in images. It enhances the precision of identifying flooded areas in complex environments.

- **UNet**: A deep learning model for semantic segmentation. UNet is used to classify flood regions from satellite imagery, providing pixel-wise flood detection and creating detailed flood maps.

---

## How to Use 🛠️

1. **Upload Data**: Upload satellite data or environmental data to the system.
2. **Run Flood Detection**: Initiate the flood detection process using the models like YOLOv5, Mask RNN, or UNet to identify flood-prone areas.
3. **Generate Predictions**: Use the flood prediction model to forecast possible flood events in the coming days.
4. **View Results**: View the detection and prediction results on the interactive visualization panel.

---

## Technologies Used 🛠️

- **Python**: For backend data processing, machine learning models, and predictions.
- **Satellite Imagery**: Data collection from platforms like NASA Sentinel and Landsat.
- **Machine Learning**: Algorithms for flood prediction (e.g., Random Forest, Neural Networks).
- **YOLOv5**: Real-time object detection for flood-affected regions.
- **Mask RNN**: Image segmentation for flood detection in satellite images.
- **UNet**: Semantic segmentation for pixel-level flood detection.
- **Leaflet.js**: For interactive map visualization.
- **Flask**: Backend framework for the web interface.
- **MySQL**: For storing and managing historical flood data.

---
