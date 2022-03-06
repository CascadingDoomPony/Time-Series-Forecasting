# Time Series Analysis

Firstly we can talk about the data we have received. From the full chart dating back to 1982, there isn't a clear overall trend up till present time, but in certain time periods we see sharp changes followed by periods of relative stability. These movements occur in around 4 year timeframes. The noise graph from the Hodrick-Prescott Filter shows that the movement of the exchange price is wide as expected.

### ARMA and ARIMA
---

The ARMA model suggests that over the next 5 days the price of the Japanese Yen will drop at varying degrees. The model, as described in the notebook, has an ok fit to the data.

The ARIMA model suggests that the yen will drop over the next 5 days as with the ARMA model.

### GARCH
---

Over the next 5 days, the GARCH model suggests that the volatility of the price of Japanese Yen will increase steadily.

### Conclusion
---

Our outputs generally say that the price will decrease over the next 5 days, but this is not necessarily enough information to make a clear trading decision, especially if the GARCH model is also suggesting that the volatility will increase

# Regression Analysis

The first thing we should note from the linear regression analysis is that the MSE is higher in-sample than out-of-sample, so the prediction data may not be very reliable. If you look very closely, the prediction trends very similarly to the actual data, but the movement is offset and the amount of change can be quite exaggerated and inaccurate.