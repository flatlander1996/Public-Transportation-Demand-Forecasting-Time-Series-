Predicting the number of passengers that arrive at a terminal for future time points. 

Due to the multiple seasonality of the time series, traditional models weren't effective so I created my own regression model with custom regressors.

•	Dataset: bicup2006 / Time-series data of passengers arriving at the terminal, sampled every 15 minutes.

•	Used: R, xts, zoo, forecast.

•	Models: Arima, TBATS, Holt-Winters, 250-variable linear model with custom regressors.

•	Accuracy: Mean Absolute Error = 5.47, Adjusted R-squared = 0.77 using my custom regression model.
