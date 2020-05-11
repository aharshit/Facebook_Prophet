# Facebook Prophet
## Predicting Apple Inc. Stock Prices Using Facebook's Prophet
In an attempt to develop a model that could capture seasonality in time series data, Facebook developed Prophet, open-source software released by Facebook’s Data Science team.Prophet is used for time series forecasting. Time series forecasting is the model used to predict future values based on previously observed values. Time series data is recorded on a discrete time scale.  
Time series forecasting is widely used for non-stationary data. Data whose statistical properties such as mean and variance are not constant over time is non-stationary data. The best example of non-stationary data is stock prices.  
Time series forecasting is widely used to predict sales and stock prices. There have been attempts to predict stock prices using time series analysis algorithms, though they still cannot be used to place bets in the real market.  
## Prophet’s equations
Prophet is an additive regression model. The following equation represents the math behind Prophet.  
  
y(t) = g(t) + s(t) + h(t) + e(t)
  
g(t) represents the trend. Prophet uses a piecewise linear model for trend forecasting.  
  
s(t) represents periodic changes (weekly, monthly, yearly).  
  
h(t) represents the effects of holidays of durations longer than a day. Holidays impact businesses.  
  
e(t) covers the changes or errors that are not covered by the model.
  
Prophet is an easy to use model. It is fast and it does not require data pre-processing. It works with missing data with several outliers. We will try to predict Apple Inc. stock prices Using Facebook’s Prophet. The daily stock prices for Apple Inc. can be downloaded from Yahoo Finance. Yahoo Finance is one of the leading sources for stock market data. We will get the data of Apple Inc. stock prices since 2015.
## Prerequisites
fbprophet, plotly
```
pip install -r requirements.txt
```
