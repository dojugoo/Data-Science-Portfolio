# Practium Project 14

## Detection of Negative Movie Reviews - Machine Learning for Text

## Description

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews.

## Conclusions

Various models and methods were tested and trained including using NLTK, spaCy, TF-IDF, and trained on logistric regression, and gradient boosting methods. All of these models achieved a F1 score on the test set of about 0.88, which meets our target metric.

I would note that improvements can be made here to tune hyperparameters, as there appears to be some overfitting of the data. For example, using LGBMClassifier, the F1 score on the train set is 0.96, while the test set is 0.87. Further parameter tuning could improve overall metrics.

BERT was used but only for a small set of data (200 rows) due to its heavy computational requirements. Further evaluation can be performed by increasing the number of samples for training.