# Practium Project 17

## Prediction of User Churn

## Description

The telecom operator, Interconnect, would like to forecast churn of their clients or the number of customers disconnecting their service over a given time period. Interconnect would like to ensure loyalty, and offer promotional codes and special plan options for those who are going to leave. The goal is to better understand why customers stay active or churned (terminate their service). Once we have a better idea of why people are leaving, the company can introduce measures to prevent ongoing churn.

The datasets include the plan's contract information, clients' personal data, information on internet services and telephone services.

## Conclusions

A model has been developed with good predictive abilities on predicting whether a user will terminate their service. More specifically, LightGBM was implemented on a binary classification task, to predict on whether users fall into two groups, churned or no churn, with a model accuracy of 88.1% and ROC-AUC of 0.93.

There are some ways that can be explored to improve the model:
- Further hyperparameter tuning should be applied. A few hyperparameters were explored here, and with more compute and time, further improvements can be made and to also improve on overfitting.
- Try other gradient boosting methods with the addition of cross-validation.
- Explore other ways to fix class imbalance. Downsampling or other methods to upsampling can be tested to determine if it improves the prediction metrics.