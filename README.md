# Time-series analysis UsingPython

Time Series Analysis: it's analysis of data which collected on certain time interval, it's very common form of data for example stock market data, daily sales data, home energy usage etc.here i am trying to do analysis of time series data

This analysis can be executed in simple 4 phases:

1. Load data
2. Check stationarity
3. Make series stationary(if not)
4. Buid model

# 1. Load data
We will use the store sales date for this, it's vaialble in data folder. it contains product sales by store and yearmonth. We can split data into train and test spliting the time frame. for example: data for 2020 can be spliyyed like train(Jan to nov) and dec(test).

# 2. Check stationarity
The series should be stationary with constant statistical properties over time.

    - constant mean
    - constant variance
    - an autocovariance that does not depend on time.
    
# 3. Make series stationary(if not)
These are two techniques widely used for removing seasonality.
    - Differencing – taking the differece with a particular time lag
    - Decomposition – modeling both trend and seasonality and removing them from the model.
    
# 4. Buid model


