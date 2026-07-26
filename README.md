# Karnataka Crop Recommendation Model

A machine learning model designed to predict and recommend the most suitable crop to cultivate based on soil nutrient levels, climatic conditions, and environmental factors specific to regions in Karnataka.

---

## 📌 Overview

This project builds a predictive model that maps environmental, soil, and weather parameters to specific crop types (`label`). 

### Feature Parameters:
* **Soil Nutrients:** Nitrogen ($N$), Phosphorus ($P$), Potassium ($K$)
* **Climate Factors:** Temperature (°C), Relative Humidity (%), Rainfall (mm)
* **Soil Properties:** pH level

---

## 📁 Dataset Information

* **File Name:** `karnataka_crop_dataset_V2.csv`
* **Features ($X$):** `N`, `P`, `K`, `temperature`, `humidity`, `ph`, `rainfall`
* **Target ($y$):** `label` (Crop name e.g., blackgram, mango, horsegram, chickpea, sapota)
* **Additional Metadata:** `soil_type`, `season`, `district`, `region`

---

## 🛠️ Requirements & Installation

Install the required Python packages before running the notebook:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
