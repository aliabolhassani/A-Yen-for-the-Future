# Time Series

## Model

The goal is to forecast return by time series analysis and modelling with CAD-JPY Exchange rate data. Hodrick-Prescott Filter uses to see the trend and noise. Forecasting will be performed using ARMA model by passing the returns to the model, and by using ARIMA model by passing the price to the model. Finally, GARCH model is used to predict the volatility of the price.

- - -

## Findings

It is found that according the initial data plotting, a long-term strengthening of the Japanese Yen against the Canadian Dollar. Also, there are a lot of short-term ups and downs. In addition, after plotting the trend using Hodrick-Prescott Filter, we can see that there is a lot of short term fluctuations that deviate around this trend. 

Also, the ARMA model seems not to be a good fit, since we have some p-values greater than 0.05. Same way, for the ARIMA model, however all the p-values are greater than 0.05, and the model looks not to be that much reliable. 

Finally, when it comes to GARCH model, since the p-values are acceptable, it seems what the forecast predicts will happen to volatility in the near future.

In conclusion, given that the value of the yen is projected to weaken against the CAD, and volatility is supposed to rise, it is suggested to hold on investing on yen at this time. Also, the risk of the yen is expected to increase increase since the volatility is going to increase.
