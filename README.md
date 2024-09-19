Sales Forecasting Using Machine Learning
This repository demonstrates how to implement and compare various machine learning models to predict monthly sales using a dataset sourced from Kaggle. The project showcases a variety of approaches, including traditional regression techniques and advanced models like LSTM and ARIMA.

Overview
The goal of this project is to forecast total monthly sales across multiple stores, utilizing 5 different machine learning models. We explore the strengths of each model and evaluate their performance based on RMSE, MAE, and R2 scores.

Models Implemented:
Linear Regression
Random Forest Regression
ARIMA (AutoRegressive Integrated Moving Average)


Data Preprocessing
Monthly Aggregation: The dataset is aggregated to represent total monthly sales.
Stationarity Transformation: Monthly sales are differenced to make the data stationary.
Feature Engineering: Lagged variables are created for regressive models to incorporate past sales data as features.

Key Steps
Load and Transform Data: The raw data is aggregated by month and preprocessed to create stationary data for modeling.
Train-Test Split: Data is split into training and testing sets, with the last 12 months used for testing.
Model Training & Evaluation: Each model is trained using historical data and then evaluated based on RMSE, MAE, and R2 scores.
Visualization: Sales predictions are compared against actual sales using plots to visualize performance.


Results
The models were compared based on their RMSE and MAE scores:

ARIMA and LSTM models followed closely, showing good potential for sales forecasting.

Conclusion
This project provides a foundational approach to sales forecasting using machine learning. It highlights the power of combining different techniques and offers a comparison to help choose the best model for different business needs.


