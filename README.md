# Credit_Risk_Analysis

In this project, we use Python to build and evaluate several machine learning models to predict credit risk:

- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.
- We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

# Results (Balanced Accuracy Scores, Confusion Matrixes and Imbalanced Classification Reports)

## Oversampling
The balanced accuracy score is 65%.
The high_risk precision is about 1% only with 62% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 68%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/Oversampling.png)

## SMOTE
The results are pretty similar to the previous model.
The balanced accuracy score is 64%.
The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 66%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/SMOTE.png)



