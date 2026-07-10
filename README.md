
# 🌱 AgriSense AI – Smart Farming Intelligence System

AgriSense AI is an **AI-powered smart farming platform** that helps farmers predict **crop yield**, **market price**, and **nutrient optimization strategies** using machine learning, deep learning, and computer vision.

This project focuses on **precision agriculture** by combining soil data, weather conditions, crop images, and economic analysis to support **data-driven farming decisions**.

---

## 🚜 Key Features

### 📊 Crop Yield & Price Prediction
- Predicts expected crop yield based on:
  - Crop type
  - Soil nutrients (N, P, K, Mg)
  - Soil pH
  - Weather conditions (temperature, rainfall, humidity)
  - Location (district/state)
- Estimates **market price** for the predicted yield

---

### 🎛 Nutrient What-If Simulator
- Interactive nutrient sliders (N, P, K, Mg)
- Real-time yield variation analysis
- Helps farmers understand **how nutrient changes affect productivity**

---

### 🌿 Crop Nutrient Deficiency Detection (Computer Vision)
- Upload crop leaf images
- Detects nutrient deficiencies:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Magnesium (Mg)
- Uses CNN-based image classification models

---

### 💰 Decision Optimization Engine
Provides two clear choices:
- **Option A:** Invest in nutrients → increased yield & profit
- **Option B:** No changes → baseline yield & income

Helps farmers make **budget-aware decisions**.

---

## 🧠 AI Models Used

| Module | Model Type |
|------|-----------|
| Yield Prediction | Random Forest / XGBoost |
| Price Forecasting | Regression + Time Series |
| What-if Analysis | Feature sensitivity modeling |
| Deficiency Detection | CNN (ResNet / EfficientNet) |

---

## 🛠 Tech Stack

- **Programming:** Python
- **Backend:** FastAPI
- **Frontend:** Streamlit / Flutter
- **ML & DL:** Scikit-learn, TensorFlow / PyTorch
- **Computer Vision:** OpenCV, CNNs
- **Data Sources:** Government agriculture & weather datasets

---

## Expected Outcome
- Improved Yield Forecasting
- Better Resource Utilization
- Data-Driven Farming Decisions
- Increased Agricultural Productivity

