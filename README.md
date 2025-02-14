# Sales-TimeSeries-Forecasting  
A time-series forecasting project that builds predictive models for store sales by addressing seasonality, trends, and other external factors. This project integrates hypothesis testing, data preprocessing, feature engineering, and applies machine learning and statistical models to make accurate predictions.

This project is part of the **[Kaggle Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)** competition.
---

## 📋 Project Overview  
This project focuses on forecasting store sales using historical data and additional features such as:  
- **Sales Data:** Daily sales figures for different product categories.  
- **Holidays:** National and regional holidays, which may influence sales trends.  
- **Oil Prices:** Economic indicators that may affect consumer spending.  
- **Store Information:** Metadata about different stores (type, location, etc.).  
- **Transactions:** The number of transactions as a proxy for foot traffic.  

### Goals  
1. Build robust forecasting models to predict future sales accurately.  
2. Identify and understand key patterns, including seasonality and trend components.  
3. Evaluate the impact of external factors (holidays, oil prices) on sales performance.  
4. Compare and analyze different machine learning and statistical forecasting approaches.

---

## ⚙️ Project Workflow  
### 1️⃣ **Data Preparation and Exploration**  
- Loaded and merged multiple datasets (sales, holidays, oil prices, etc.)  
- Performed exploratory data analysis (EDA) to identify key patterns  
- Hypothesis testing to assess the impact of holidays and oil prices on sales  
- Data preprocessing and feature engineering for model readiness  

### 2️⃣ **Modeling**  
Implemented and compared several forecasting models:  
- **Statistical Models:** ARIMA, Exponential Smoothing, Holt-Winters  
- **Machine Learning Models:** Random Forest, XGBoost, LightGBM  
- **Time Series Models:** Prophet for seasonality and trend analysis  

### 3️⃣ **Evaluation and Performance Metrics**  
Used multiple performance metrics to assess the accuracy of each model:  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

---

## 📊 Key Findings  
- **Seasonality:** Detected strong weekly and yearly seasonal patterns in sales.  
- **Holidays:** Observed significant impact of national holidays on sales.  
- **Oil Prices:** Found no substantial correlation between oil prices and sales.  

---

## 🔧 Tech Stack  
- **Programming Languages:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, statsmodels, xgboost, lightgbm, Prophet, matplotlib, seaborn  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook, Google Colab  
