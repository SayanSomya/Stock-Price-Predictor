# Stock market forecasting using Time Series Analysis:💵

### What is a Stock market?

The stock market is a market that enables the seamless exchange of buying and selling of company stocks. Every Stock Exchange has its own Stock Index value. The index is the average value that is calculated by combining several stocks. This helps represent the entire stock market and predict the market’s movement over time. The stock market can have a huge impact on people and the country’s economy. Therefore, predicting the stock trends efficiently can minimize the risk of loss and maximize profit.

 #### We will forecast the stock price of **ARCH CAPITAL GROUP** using **ARIMA model**

### What is **ARIMA**?
*Autoregressive Integrated Moving Average* (ARIMA) Model converts non-stationary data to stationary data before working on it. It is one of the most popular models to predict linear time series data.

ARIMA model has been used extensively in the field of finance and economics as it is known to be robust, efficient and has a strong potential for short-term share market prediction.

### What is **Time Series Analysis**?
The given time series is thought to consist of three systematic components including level, trend, seasonality, and one non-systematic component called noise.
These components are defined as follows:

1. **Level**: The average value in the series.
2. **Trend**: The increasing or decreasing value in the series.
3. **Seasonality**: The repeating short-term cycle in the series.
4. **Noise**: The random variation in the series.

For that, we need to check if a series is stationary or not because time series analysis only works with stationary data.

**ADF (Augmented Dickey-Fuller) Test**
The Dickey-Fuller test is one of the most popular statistical tests. It can be used to determine the presence of unit root in the series, and hence help us understand if the series is stationary or not. The null and alternate hypothesis of this test is:
1. **Null Hypothesis**: The series has a unit root (value of a =1)
2. **Alternate Hypothesis**: The series has no unit root.
   
If we fail to reject the null hypothesis, we can say that the series is non-stationary. This means that the series can be linear or difference stationary.

If both mean and standard deviation are flat lines(constant mean and constant variance), the series becomes stationary.
