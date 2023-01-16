# Practium Project 8

## Bank Customers - Supervised Learning

## Description

Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.

## Conclusions

The best model was determined to be a random forest model and the quality was improved by upsampling the data and improving the class imbalance. 

The resulting metrics had an accuracy of 0.811, F1 score of 0.608, and AUC-ROC of 0.853.

F1 score is a score that ranges from 0 to 1, where 0 is the worse and 1 is the best possible score. It is evaluated from both the recall and precision metrics. It was achieved to have a F1 score greater than 0.59 as the target.

AUC-ROC or aurea under the curve for receiver operating characteristic, this score ranges from 0.5 to 1, where 0.5 means the model is as good as random, and where 1 is the best score. This metric is the relationship between the true positive rate (TPR) and the false positive rate (FPR) of the model. Having a AUC-ROC of 0.853 means that our model is better than random, but not perfect.