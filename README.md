# 🛋️ Univariate Time Series Forecasting – Furniture & Home Furnishings
This project involves univariate time series forecasting for monthly sales data of furniture and home furnishings stores. The data was collected from an open-source government website. The objective is to build accurate ARIMA and SARIMA models in Python to forecast future sales and support retail planning decisions such as inventory and supply chain management. The project includes data cleaning, stationarity testing, model development, and forecast visualization..

## 📊 Project Overview

- **Goal**: Forecast sales to help optimize inventory and supply chain planning.
- **Data**: Monthly retail sales data from a open-source public government dataset.
- **Techniques**:
  - Time series cleaning & preprocessing
  - Stationarity check with ADF Test
  - Differencing to remove trends/seasonality
  - ARIMA and SARIMA model building
  - Model evaluation & visualization

## 🛠️ Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- statsmodels
- pmdarima

## 📈 Key Steps

1. Loaded and preprocessed time series data
2. Handled missing values
3. Made the series stationary
4. Fitted ARIMA and SARIMA models
5. Forecasted sales for the next 12 months
6. Visualized predictions vs actuals

## 📌 Results

- Accurate short-term forecasting using SARIMA
- Visual insights into seasonality patterns
