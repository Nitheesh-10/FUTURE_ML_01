🧠 AI-Powered Sales Forecasting Dashboard (Power BI + Python)

This project is an AI-driven sales forecasting system that combines Python’s machine learning capabilities (via LightGBM) with Power BI’s interactive dashboarding features.
It enables accurate sales prediction, trend visualization, and performance tracking — all within a dynamic Power BI interface.

🚀 Project Overview

Traditional sales forecasting often struggles with seasonality, promotions, and sudden demand shifts.
This project automates the process using machine learning to predict future sales and integrates results seamlessly into Power BI.

Key features:

Forecasts future sales using LightGBM Regression

Includes time-series feature engineering (lags, rolling means, seasonality)

Outputs forecasted data (forecast.csv) ready for Power BI visualization

Includes error metrics (MAE, RMSE) for evaluation

Produces forecast plots for model performance analysis

Supports single-store or multi-store forecasting

🛠 Future Improvements

Add multi-store forecasting loop

Incorporate holiday and weather data

Support Prophet or XGBoost models for comparison

Integrate AutoML pipeline

Build scheduled retraining via Power Automate or Azure Functions

Deploy to Power BI Service with OneDrive auto-refresh
