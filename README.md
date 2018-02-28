# Forecasting Bankruptcy Rate using Time Series

This project is completed in collaboration with Jose A. Rodilla, Zizhen Song, Kaya Tollas and we achieved the highest accuracy among all the teams.


Using historical data of 22 years, this model forecasts Canada's monthly bankruptcy rate for two years. A multi variate time series approach is considered for forecasting because we had data for unemployment rate, population and housing price index for both train and test time span.

Implemented different time series models such as ARIMA, ARIMAX, SARIMA, SARIMAX, VAR, VARX, Holt-Winters and Exponential Smoothing and Elastic Net in R for accurate predictions and prevented overfitting using a validation set. Finally, combining two SARIMA models yielded the best result.


The raw code for the project can be found [here](https://github.com/arpitaj5/TS_BankruptcyRate_Forecasting/blob/master/forecasting.Rmd). Currently, it contains only the models generating optimal result. In future, I will update it with all the test cases and residual diagnostics.

Here is the [project report](https://github.com/arpitaj5/TS_BankruptcyRate_Forecasting/blob/master/Project_Report.pdf) for further details around the modeling techniques.
