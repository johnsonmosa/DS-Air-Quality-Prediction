# 🌫️ Air Quality Prediction & Analysis Website

This project is a user-friendly web application built to **analyze, visualize, and predict Air Quality Index (AQI)** using machine learning and time-series data techniques. It supports environmental insight and early warning systems for pollution spikes through powerful data science tools and intuitive visualizations.

---

## 📌 Problem Statement

Air pollution remains a global health and environmental threat, particularly in urban areas. Traditional monitoring is often expensive and lacks predictive power. This project leverages **machine learning regression models** to forecast AQI using pollutant and meteorological data.

---

## 🎯 Objectives

- Predict AQI using PM2.5, PM10, NO2, SO2, CO, O3, temperature, humidity, wind speed, and date.
- Perform data cleaning, transformation, and feature engineering.
- Visualize pollutant trends and forecast AQI values using regression models.
- Compare performance of models like **Random Forest** and **XGBoost**.
- Extract feature importance to understand key pollution drivers.

---

## 🗂️ Dataset

- **Name:** Synthetic Air Quality Dataset  
- **Type:** Tabular time-series  
- **Records:** ~720+  
- **Features:** PM2.5, PM10, NO2, SO2, CO, O3, Temperature, Humidity, Wind Speed, Date  
- **Target:** AQI (Air Quality Index)

---

## ⚙️ Features of the Application

### ✅ Data Preprocessing
- Median imputation for missing values  
- Duplicate and outlier removal  
- Date format conversion  
- Min-Max normalization  

### 📊 Exploratory Data Analysis (EDA)
- Histograms for pollutant distribution  
- Correlation heatmap  
- Seasonal insights on AQI patterns  

### 🧠 Feature Engineering
- Month and Day of Week extraction  
- PM2.5 / PM10 ratio  
- Lag features for time-series prediction  
- Optional PCA for dimensionality reduction  

### 🤖 Model Building
- **Random Forest Regressor**
- **XGBoost Regressor**
- 80/20 train-test split  
- Metrics: MAE, RMSE, R² Score  

### 📈 Visualization
- Predicted vs Actual AQI plot  
- Residual and error distribution plots  
- Feature importance bar chart  

---

## 🛠️ Technologies Used

| Category        | Tools & Libraries                                    |
|-----------------|------------------------------------------------------|
| Platform        | Google Colab / Local Python                          |
| Language        | Python                                               |
| ML Libraries    | scikit-learn, xgboost                                |
| Visualization   | matplotlib, seaborn, plotly                          |
| Data Handling   | pandas, numpy                                        |
| Time Series     | datetime                                             |

---

## 🚀 How to Use

1. Open the app or notebook interface.
2. Upload the `synthetic_air_quality_data.csv` file.
3. Select which model (Random Forest or XGBoost) you want to evaluate.
4. View detailed insights through charts, error plots, and feature importance.
5. Optionally upload your own dataset to test.

---

## 📚 Team Contributions

- **Benedict Edwin.A (Team Lead):** Core modeling, dataset creation, final integration  
- **Johnson G:** EDA visuals, pollutant trend analysis  
- **Janani.V:** Feature engineering, UI interface, documentation  

---

## 📌 Status

✅ Phase 1 – Complete  
✅ Phase 2 – Complete  
🚧 Deployment – Available via Colab notebook or local execution

---

## 📎 License

This project is for educational use only. Dataset is synthetic and privately generated.

---

## 📬 Contact

**Johnson G**  
Dept. of AI & DS, Christ The King Engineering College  
📧 johnsonmosa755@gmail.com 
📍 Tamil Nadu, India
