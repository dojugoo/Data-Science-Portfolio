# Practium Project 11

## Insurance Customers

## Description

The Sure Tomorrow insurance company wants to solve several tasks with the help of Machine Learning and you are asked to evaluate that possibility.

- Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
- Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a prediction model do better than a dummy model?
- Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without breaking the model from the previous task. It's necessary to develop a data transformation algorithm that would make it hard to recover personal information if the data fell into the wrong hands. This is called data masking, or data obfuscation. But the data should be protected in such a way that the quality of machine learning models doesn't suffer.

## Conclusions

We have explored the use of k-Nearest Neighbor to find customers that are similar to one another. The analysis shows that to get a better result, the features need to be scaled or else certain features are weighted differently due to its values. Furthermore, the effects of the distance metric between Euclidean or Manhattan has very little effect on the results.

Next, we trained a kNN classifier model to predict whether a person will receive insurance benefits or not. Again, scaling the features is critically important, as the trained model resulted in a F1 score of 0.92, compared to a dummy model (binomial random prediction) F1 score of 0.20.

Linear regression model can be used to predict the number of insurance benefits. In this case, we show that the features does not need to be scaled as the resulting predictions had the same RMSE and R2 metrics with and without scaling.

Finally, we show that personal information data can be obfuscated by multiplying the features with an invertible matrix. The resulting information can be recovered, and that linear regression model can be used on both the obfuscated and non-obfuscated data with no issues. 