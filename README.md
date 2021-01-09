# A Yen for the Future

![Yen Photo](Images/unit-10-readme-photo.png)

## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

We will test the many time-series tools in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.

The following tasks will be performed:

1. Time Series Forecasting
2. Linear Regression Modeling


- - -

### Files

Use the following starter code: 

Note: The starter code shows example calculations and figures to use as a guide.

[Time-Series Starter Notebook](Starter_Code/time_series_analysis.ipynb)

[Linear Regression Starter Notebook](Starter_Code/regression_analysis.ipynb)

[Yen Data CSV File](Starter_Code/yen.csv)

- - -

#### Time-Series Forecasting

Apply time series analysis and modeling to determine whether there is any predictable behavior from historical Dollar-Yen exchange rate futures data.

Notebook:

1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.

### Analysis

 1. Medium-risk, High-risk investors would consider buying to maximize returns.
 2. The risk is excepted to increase along with volatility. 
 3. The ARIMA and GARCH models produce confident outputs related to probability to use for trading. 


#### Linear Regression Forecasting

Building a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with *lagged* Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

Regression_analysis starter notebook:

1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

* The Out-Of-Sample RMSE is lower than the In-sample RMSE. 
* Typically the training data is lower but is higher in the data above.

- - -
