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

## 📊 Forecast Results & Visuals
Below are key visualizations from the ARIMA and SARIMA forecasting models:

### 🔹 Series After Differencing (Stationarity Check)
![Image](https://github.com/user-attachments/assets/ecfb7d79-1c46-4d9a-abb2-6c2e2c400a78)


### 🔹 ARIMA Forecast (Actual vs Predicted)
![Image](https://github.com/user-attachments/assets/e9294454-dee2-43c6-8f99-d4380c7daead)

### 🔹 SARIMA Forecast (Actual vs Predicted)
![Image](https://github.com/user-attachments/assets/4583eae2-2150-4946-b40f-7d854ee797b0)

### 🔹 Full Time Series Forecast with Future Predictions
![Image](https://github.com/user-attachments/assets/db88816b-0e68-448e-a05c-427ddbe1ee76)


##  📈 Insights 
- Seasonality Detected: Monthly sales data shows clear seasonal trends, especially high sales in November and December, possibly due to holidays or year-end promotions.

- Stationarity Achieved: The original series was non-stationary. Stationarity was achieved after applying first-order differencing.

- SARIMA > ARIMA: SARIMA performed better than ARIMA because it handled seasonal components effectively.

- Model Fit: Forecasts closely matched actual values during the test period, indicating a strong model fit.

- Forecast Horizon: The model reliably predicts sales for the next 12 months, providing valuable insights for planning.

## 🏪 Business Recommendations
- Inventory Planning:
   - Stock levels should be increased ahead of high-demand months (especially Oct–Dec) to avoid stockouts and lost sales.

- Promotional Strategy:
   - Run marketing campaigns and discounts during low-sales months (e.g., Feb, May) to boost demand.

- Supply Chain Optimization:
   - Use the sales forecast to inform purchase orders and logistics planning in advance — reducing excess inventory and storage costs.

- Data-Driven Budgeting:
   - Use forecasted sales to create monthly revenue targets and align budgeting decisions accordingly.

- Model Re-Training:
  - Update the forecasting model with new sales data every quarter to maintain accuracy and capture new trends or seasonality changes.

