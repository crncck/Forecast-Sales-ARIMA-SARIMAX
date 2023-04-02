# Forecast-Sales-ARIMA-SARIMAX

This project contains the examples of using time series to predict on future sales with ARIMA and SARIMAX algorithms. 

The dataset is [Perrin Freres Monthly Champagne Sales dataset](https://www.kaggle.com/datasets/anupamshah/perrin-freres-monthly-champagne-sales) and it contains monthly sales of champagne from year 1964 to 1972. 

Before applying ARIMA and SARIMAX algorithm, the data must be stationary. 

So we should check if our data is stationary, for this, we conducted the Augmented Dickey-Fuller test. The data was not stationary and we turned it to stationary. Then we applied ARIMA, but this algorithm was not good at prediction because the data was seasonal. The ARIMA is not suitable for seasonal data. But for seasonal data, there is another algorithm called SARIMAX (seasonal ARIMA), which is an extension of ARIMA. Using SARIMAX, we made forecasting on future data.

<br>

<img src="https://iili.io/HOCBlIt.png" /> 
