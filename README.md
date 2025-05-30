# 🛒 Store Sales - Time Series Forecasting

This project is based on the **Kaggle competition**:  
[Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

The goal is to forecast daily sales for a large grocery chain in Ecuador, using historical data enriched with calendar, promotion, and holiday information.

---

## 📂 Dataset Overview

The dataset includes:
- Daily sales records for multiple stores
- Promotion flags
- Local and national holidays
- Date-based patterns

> 📌 **Note**: The data is provided by Corporación Favorita via Kaggle for educational and research purposes.

---

## 🎯 Project Objectives

- Analyze and visualize sales patterns over time
- Engineer meaningful time series features (lags, rolling stats, date components)
- Build and compare forecasting models:
  - Traditional (ARIMA/SARIMA)
  - Machine learning (XGBoost)
  - Deep learning (optional: LSTM, Transformer)
- Evaluate results with MAE, RMSE, and SMAPE
- Interpret model performance across stores
