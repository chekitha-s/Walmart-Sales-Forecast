# Walmart Sales Forecast

### Project Overview
This project tackles the M5 Forecasting Accuracy challenge from Kaggle, which aims to predict Walmart’s daily product sales across three U.S. states. Accurate demand forecasting is crucial for inventory management, supply chain optimization, and business planning. The task focuses on generating 28-day ahead forecasts using historical sales and auxiliary signals.

### Dataset
Source: Kaggle M5 Forecasting Accuracy
Scope: ~30,000 products across 10 Walmart stores in California, Texas, and Wisconsin
Features:
1. Daily sales from 2011–2016 (1,913 days)
2. Product hierarchy (item, department, category)
3. Price, promotions, special events, and calendar variables

### Methodology
1. Exploratory Data Analysis (EDA): Identified demand patterns, seasonality, and state-level variations.
2. Feature Engineering: Lag features, rolling averages, price/event encoding.
3. Modeling: Compared statistical (ARIMA, SARIMA) vs. machine learning models (Random Forest, XGBoost).
4. Evaluation: Used MAE and RMSE to measure forecast accuracy.

### Results
XGBoost delivered the best performance, handling seasonality and promotions effectively.
Outperformed ARIMA/SARIMA with lower MAE and RMSE.
Produced stable forecasts across categories, with particularly strong results in food and household products.

### Conclusion
Tree-based models such as XGBoost proved most effective for short-term Walmart demand forecasting. These insights can directly support inventory planning and cost reduction while maintaining high forecast accuracy.
