# Practium Project 10

## Gold Recovery - Machine Learning Model

## Description

Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry. The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification. The model will help to optimize the production and eliminate unprofitable parameters.

Mined ore undergoes primary processing to get the ore mixture or rougher feed, which is the raw material for flotation (also known as the rougher process). After flotation, the material is sent to two-stage purification.

1. Flotation

Gold ore mixture is fed into the float banks to obtain rougher Au concentrate and rougher tails (product residues with a low concentration of valuable metals).
The stability of this process is affected by the volatile and non-optimal physicochemical state of the flotation pulp (a mixture of solid particles and liquid).

2. Purification

The rougher concentrate undergoes two stages of purification. After purification, we have the final concentrate and new tails.

We need to predict two values:

- rougher concentrate recovery `rougher.output.recovery`
- final concentrate recovery `final.output.recovery`

Evaluation metric: symmetric Mean Absolute Percentage Error (sMAPE)

## Conclusions

The metric final sMAPE between a trained random forest model on the prediction of gold recovered is 9.43, compared to a baseline constant model predicting the mean of the test set with a final sMAPE of 10.29.

The trained model does show an improvement in prediction. Whether this ~0.9% improvement is significant or not for their purposes, but it could make a difference as cost savings and profitability can improve at larger scales.

There are a couple areas where the trained model can be improved. Any additional information on the features can help guide how to process the data even more to have a better fit to the models. Another is that the test set may have some slight differences between the training set, so the predictions can be negatively affected.