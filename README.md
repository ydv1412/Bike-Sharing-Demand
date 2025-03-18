# 🚴‍♂️ Bike Sharing Demand Prediction

This repository contains the **Bike Sharing Demand Prediction** project, which aims to forecast the number of rental bikes required at any hour of the day. The project is part of a **Capstone Project** and leverages **data analysis and machine learning models** to achieve accurate predictions.

## 📌 Problem Statement

With the rise of **bike rental systems in urban cities**, it is essential to ensure an optimal supply of bikes to minimize waiting time and improve accessibility. This project **predicts hourly bike demand** using historical data, considering factors like temperature, humidity, seasons, and holidays.

## 📊 Data Summary

- **Dataset Size**: 8760 rows, 14 features.
- **Key Features**:
  - **Numeric**: Temperature, Humidity, Wind Speed, Visibility, Solar Radiation, etc.
  - **Categorical**: Seasons, Holidays, Functioning Days.
  - **Target Variable**: Number of rented bikes per hour.

## 🔍 Exploratory Data Analysis

- **Bivariate & Univariate Analysis**: Identified correlations between weather conditions and rental patterns.
- **Key Insights**:
  - Rentals peak at **8 AM, 6 PM, and 7 PM**.
  - **Summer** has the highest rental counts, while **winter** has the lowest.
  - **Rainfall & snowfall negatively impact** rental demand.

## 🏆 Machine Learning Models

The following models were trained and evaluated:

| Model                      | Mean Squared Error (MSE) | R² Score |
|----------------------------|-------------------------|----------|
| KNN Regressor              | 284                     | 0.82     |
| Linear Regression          | 431                     | 0.60     |
| Support Vector Regressor   | 529                     | 0.51     |
| Decision Tree Regressor    | 244                     | 0.87     |
| **Random Forest Regressor** | **162**                 | **0.94** |
| Gradient Boosting Regressor | 218                     | 0.90     |

- **Best Model**: **Random Forest Regressor** with an **MSE of 162** and **R² score of 0.94**.
- **Feature Importance**: Hour and temperature were the most influential factors.

## ⚡ Conclusion

- The **dataset was well-structured and clean**, allowing straightforward model development.
- **Random Forest Regressor** outperformed other models in prediction accuracy.
- Future improvements could explore **deep learning approaches** or additional **external features**.

## 🏗 Challenges

- The dataset was **clean and well-balanced**, making the analysis and modeling process smooth.
- No missing values were encountered.

---

### 📂 Files
- **Bike Sharing.pdf** - Detailed project report including analysis and results.

---

## 🛠 Future Work

- Implement **deep learning** models (e.g., LSTMs) for time-series forecasting.
- Integrate **real-time weather data** to enhance prediction accuracy.
- Optimize model hyperparameters for even better performance.


