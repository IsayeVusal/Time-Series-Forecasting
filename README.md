# Time-Series-Forecasting
Time series are stationary if they do not have trend or seasonal effects. Summary statistics calculated on the time series are consistent over time, like the mean or the variance of the observations.

An ARIMA model can be created using the statsmodels library as follows:

1.Define the model by calling ARIMA() and passing in the p, d, and q parameters.

2.The model is prepared on the training data by calling the fit() function.

3.Predictions can be made by calling the predict() function and specifying the index of the time or times to be predicted.
