Advanced Time Series Forecasting with Uncertainty
Project Overview

This project demonstrates multivariate time series forecasting using a deep learning model (LSTM) with uncertainty quantification. The model predicts multiple future time steps and estimates prediction uncertainty using Monte Carlo Dropout. The results are evaluated using error metrics and compared with a traditional statistical model (SARIMAX).

Key Features
Multivariate time series data (3 input features)
LSTM-based deep learning model
Multi-step forecasting
Uncertainty estimation using Monte Carlo Dropout
80% and 95% prediction intervals
Coverage analysis for uncertainty evaluation
Baseline comparison using SARIMAX
Single-file, end-to-end implementation

Project Structure
advanced_time_series_with_uncertainty.py
README.md

Requirements
Install the required Python libraries:
pip install numpy pandas matplotlib scikit-learn tensorflow statsmodels

How to Run
Execute the script using:
python advanced_time_series_with_uncertainty.py

The script will:
Train the LSTM model
Generate multi-step forecasts
Compute uncertainty intervals
Print evaluation metrics
Display forecast visualization

Evaluation Metrics
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
Prediction Interval Coverage (80% & 95%)

Output
Console output with model comparison and uncertainty metrics
Plot showing actual vs predicted values with uncertainty bands

Baseline Model
A SARIMAX model is used as a statistical baseline to compare performance with the deep learning approach.

Author
Preetha Devi

Conclusion
This project shows how deep learning models can be enhanced with uncertainty estimation techniques to produce more reliable and interpretable time series forecasts.
