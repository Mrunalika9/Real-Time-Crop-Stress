# Real-Time-Crop-Stress
# 🌾 Real-Time Crop Stress Detection using Weather + NDVI (Machine Learning Project)

This project predicts crop stress levels (High, Moderate, Low) based on real-time weather data from NASA and simulated NDVI values. It uses a machine learning model (Random Forest Classifier) and evaluates it with classification metrics.

## 🚀 What It Does
- Fetches temperature & humidity from NASA POWER API
- Simulates NDVI values for the location
- Classifies crop stress level
- Shows a full classification report
- Visualizes NDVI trends over time

## 📦 Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy, Matplotlib
- NASA POWER API
- Google Colab

## 📈 Output Sample
![NDVI Chart](ndvi_chart.png) *(screenshot from the chart)*

## 👨‍🌾 Use Case
This project is useful for agricultural monitoring, especially in resource-constrained areas where real-time stress evaluation can help prevent crop failure.

---

## ✅ How to Run
1. Clone this repo or open `crop_stress_detector.ipynb` in Google Colab.
2. Run all cells. Input any valid location.
3. You'll see real-time weather, NDVI, classification, and predictions.

---

## 📸 Screenshots
- Classification report  
- NDVI chart  
- Input/output sample
