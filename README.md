# BTP2
## Forecasting Particulate Matter 2.5 concentration in Delhi and Mumbai  
Objective: The primary aim of this research is to develop a robust and accurate model for forecasting hourly and daily PM2.5 concentration levels in Delhi and Kolkata using the latest time series data. This study seeks to compare and analyze the PM2.5 levels in these cities, identify patterns and trends, and predict future PM2.5 concentrations using both univariate and multivariate time series models.  
* Total 12 univariate models are trained, 3 models for each dataset (1 SARIMA model, 1 Prophet model, 1 LSTM) and 8 multivariate models are trained 2 models for each dataset(1 LSTM with fully connected layer model, 1 1D-CNN with fully connected layer model)
* Got mean absolute error of 5.3 for Kolkata Daily Dataset, mean absolute error of 5.2 for Kolkata Hourly Dataset, mean absolute error of 8.4 for Delhi Daily Dataset and mean absolute error of 12.32 for Delhi Hourly Dataset. 
