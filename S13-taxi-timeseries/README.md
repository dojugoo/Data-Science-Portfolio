# Practium Project 13

## Taxi Data - Time Series Prediction

## Description

Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.

## Conclusions

Using the median of the test set, the resulting MAE and RMSE is 44.8 and 58.7, respectively. Using the previous value to predict the next value, the resulting MAE and RMSE is 45.0 and 58.9, respectively.

CatBoost trained model shows an improved prediction quality in forecasting number of taxi orders. The metrics on the test set is MAE: 32.4 and RMSE: 43.2, meeting our criteria of having a RMSE under 48, and overall better metrics over the baseline models.