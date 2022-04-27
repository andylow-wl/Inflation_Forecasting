# Inflation_Forecasting
Canada's inflation rate forecasting using Autoregression, Random Forest and Long Short Term Memory(LSTM). The data were taken from the following sources and split into Pre-covid period and Covid period. The models were trained using 407 macroeconomic variables. 1,6 and 12-step ahead forecast models were created for each model.  

# Data Sources:
- https://www.stevanovic.uqam.ca/DS_LCMD.html
- https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000601

# Pre-Covid Results
 Model  | 1-step RMSE | 6-step RMSE | 12-step RMSE |   
| ------------- | ------------- | ------------- | ------------- | 
| AR(2)  | 0.00208 | 0.00534 | 0.007109 | 
| Random Forest | 0.000710 | 0.00489 | 0.00595 | 
| LSTM  | 0.00112 | 0.00522 | 0.00719 | 

# Covid Results
 Model  | 1-step RMSE | 6-step RMSE | 12-step RMSE |   
| ------------- | ------------- | ------------- | ------------- | 
| AR(2)  | 0.00346 | 0.0135 | 0.0195 | 
| Random Forest | 0.00141 | 0.0119 | 0.0207 | 
| LSTM  | 0.00206 | 0.0114 | 0.0198 | 

# AR(2) 1-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/AR2_1.PNG)

# AR(2) 6-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/AR2_6.PNG)

# AR(2) 12-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/AR2_12.PNG)

# Random Forest 1-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/RF_1.PNG)

# Random Forest 6-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/RF_6.PNG)

# Random Forest 12-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/RF_12.PNG)

# LSTM 1-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/LSTM_1.PNG)

# LSTM 6-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/LSTM_6.PNG)

# LSTM 12-step forecast
![](https://github.com/andylow1704/Inflation_Forecasting/blob/main/Images/LSTM_12.PNG)
