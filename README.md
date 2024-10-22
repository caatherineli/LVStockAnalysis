# LVMH Stock Analysis Report

Project Overview: This report analyzes the stock performance of LVMH (LVMUY) using time series forecasting and spectral analysis. By applying the Seasonal Autoregressive Integrated Moving Average (SARIMA) model, we aim to identify trends and predict future stock prices.

*Data and Methodology:*
* The dataset contains historical closing prices of LVMH stock.
* Initial data exploration includes visualizing the time series, calculating the autocorrelation (ACF), and partial autocorrelation (PACF).
* A log transformation followed by differencing is performed to stabilize the variance and make the series stationary.

*Modeling:*
* Various SARIMA models are fitted, with ARIMA(1,0,5) showing the lowest Akaike Information Criterion (AIC), indicating it as the best model.
* Diagnostic checks of the residuals confirm the model's adequacy.
  
*Forecasting:* Future stock prices are forecasted for the next 12 periods, providing insights into expected trends.

*Spectral Analysis:* A periodogram is computed to examine the frequency components of the stock price movements, revealing underlying cyclical patterns.
