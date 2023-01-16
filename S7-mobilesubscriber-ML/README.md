# Practicum Project 7

## Mobile Carrier Subscriber Plan - Machine Learning

## Description

The goal of this project is to evaluate three different machine learning classification models, Decision Tree, Random Forest, and Logistic Regression, and identifying the best model and parameters to predict behaviors of Megaline subscribers. The dataset from 'users_behavior.csv' will be used to train and validate the machine learning models. Finally, a test set will be used to check the quality of the models.

Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.
You have access to behavior data about subscribers who have already switched to the new plans. For this classification task, you need to develop a model that will pick the right plan.

## Conclusions

Decision Tree model accuracy on test set is 0.81.

Random Forest model accuracy on test set is 0.80.

Logistic Regression model accuracy on test set is 0.68, which is equivalent to the minimal quality model, so the logistic regression model is not a reliable model to use.

After evaluating with the test set, the ranking of the models: decision tree > random forest > logistic regression. The decision tree accuracy actually went up on the test set, while the accuracy of the random forest model went down when evaluating the test set. The change in difference is actually fairly small and likely not that significant of a difference. From this analysis though, we were able to achieve accuracy on a test dataset of more than 75% with both decision tree and random forest models.