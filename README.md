# Forecasting-Including-ARIMA

We are forecasting the value of life expectancy from the data collected from gapminder website. We will be using multiple forecasting model and comparing respective accuracy to find the best fit model.

# Data

Data we have used is collected from Gapminder website. With 1960-2010 as the data points to build the forecasting models and another 7 data points from 2011-2017 to test the accuracy of these models. For Bivariate regression and multivariate regression we have used child mortality rate for dependent variable and respective dummy variable for any structural instability. 

# Methods

Extrapolative Methods:
1. Naive
2. Moving Average (3,4,5 Years)
3. Exponential Smoothing (Simple, Holt's Linear Trend, Damped Trend)
4. ARIMA (0,2,6)

Explanatory Methods:
1. Bivariate Regression
2. Multivariate Regression with Dummy
3. Multivariate Regression with Slope and Intercept dummy

#Conclusions

•	In general Extrapolative methods provide accurate result compared to Explanatory Methods. 
•	But, Multivariate regression with slope and intercept dummy provided highest accurate result followed by Naïve method. 
•	Every Method used here are efficient to be used in forecasting as MAPE % is lower than 2%. Relative accuracy can be observed from rank column for these models used. 
