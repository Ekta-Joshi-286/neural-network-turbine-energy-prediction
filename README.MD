# ⚙️ Turbine Energy Yield (TEY) Prediction using Neural Networks

## 📌 Project Overview
Gas turbines are widely used in power generation, and their energy output is strongly influenced by ambient environmental conditions.  
This project focuses on **predicting Turbine Energy Yield (TEY)** using a **Neural Network regression model built with Keras**.

The model learns **non-linear relationships** between ambient variables and turbine performance.

---

## 🎯 Problem Statement
Predict the **Turbine Energy Yield (TEY)** using ambient environmental variables collected from a gas turbine system.

---

## 📊 Dataset Information
- **Total records:** 36,733
- **Data type:** Hourly aggregated sensor measurements
- **Target variable:** `TEY` (Turbine Energy Yield)

### Ambient Features Used:
- **AT** – Ambient Temperature
- **AP** – Ambient Pressure
- **AH** – Ambient Humidity

---

## 🧹 Data Preprocessing
- Selected only ambient variables as input features
- Applied **train-test split**
- Used **StandardScaler** for feature scaling
- Ensured clean numeric input for Neural Network training

---

## 🧠 Model Used
- **Neural Network (Regression)**
- Built using **TensorFlow / Keras**
- Architecture:
  - Input layer
  - Hidden layers with ReLU activation
  - Output layer with linear activation

---

## ⚙️ Model Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

These metrics help assess prediction accuracy and model reliability.

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

