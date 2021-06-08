# Credit_Risk_Analysis

In this project, we use Python to build and evaluate several machine learning models to predict credit risk:

- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.
- We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.


# Results (Balanced Accuracy Scores, Confusion Matrixes and Imbalanced Classification Reports)

## OVERSAMPLING
The balanced accuracy score is 65%.
The high_risk precision is about 1% only with 61% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 68%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/Oversampling.png)

## SMOTE
The results are pretty similar to the previous model.
The balanced accuracy score is 64%.
The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 66%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/SMOTE.png)

## ENSEMBLE CLASSIFIER
Now, the balanced accuracy score is high to about 93%.
The high_risk precision is still low at 7% only with 91% sensitivity which makes a F1 of only 14%.
Due to a lower number of false positives, the low_risk sensitivity is now 94% with 100% presicion.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/EnsembleClassifier.png)

## RANDOM FOREST
The balanced accuracy score improved to about 79%.
The high_risk precision is still low at 4% only with 67% sensitivity which makes a F1 of only 7%.
Due to a lower number of false positives, the low_risk sensitivity is now 91% with 100% presicion.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/BalancedRandomForest.png)

## SMOTEENN
The balanced accuracy score is about 62%.
The high_risk precision is still 1% only with 68% sensitivity which makes a F1 of only 2%.
Due to the high number of false positives, the low_risk sensitivity is 57%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/CombOverUnder.png)

## UNDERSAMPLING
Here the balanced accuracy score is down to about 52%.
The high_risk precision is still 1% only with 63% sensitivity which makes a F1 of 1%.
Due to the high number of false positives, the low_risk sensitivity is only 40%.

![alt text](https://github.com/Susanaecorreia/Credit_Risk_Analysis/blob/main/linear_regression_salary/Undersampling.png)


# Summary

All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. However, overall, the best model that was generated to predict the unbalanced classification problem of credit risk is the Ensemble Classifier, therefore I would recommend the Ensemble Classifier due to its higher overall scores for a classification prediction.


