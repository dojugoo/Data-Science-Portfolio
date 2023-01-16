# Practium Project 12

## Prediction of Used Car Prices

## Description

Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. 

Rusty Bargain is interested in:

- the quality of the prediction;
- the speed of the prediction;
- the time required for training

## Conclusions

Overall, with the used car data set, LightGBM method had the best properties in terms of quality of the prediction and speed of training and prediction. The mean and standard deviation of the `price` target is 4416 +/- 4514. Considering this, the method prediction had a RMSE value of 1735. Compared with non-gradient boosting methods, such as decision tree or linear regression, the respective RMSE for the predictions are 2540 and 3180, so the gradient boosting method is considerably better.

To summarize the workflow, the data set was prepared by removing duplicate rows, filled missing values, and categorical columns were encoded using one-hot encoding for models that require encoding. Next, non-gradient boosting and gradient boosting methods were evaluated, with hyperparameter tuning. Non-gradient boosting methods included DecisionTreeRegressor, RandomForestRegressor, and LinearRegression, while gradient boosting methods included LightGBM, CatBoost, and XGBoost. 