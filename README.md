# Cohort-Churn-Analysis-by-kd

Performed cohort analysis on the telecom data .

Findings & Observations:
>Customer with short-term-contract is more likely to churn.
>Customer with one & two-year contract tends to churn less and churn if they have high total charges.
>Internet Service is also an important feature that directly correlates to churning.
>A general trend can be seen as the longer the tenure of the cohort, the less of a churn rate.
Predictive Modeling:
Because of the data being slightly imbalanced machine learning model tends to be biased towards the prediction of majority classes and over-classifies them.
Used different class weights for the two classes and evaluated the model based on F1 score and recall metrics. Also, used SMOTE technique to oversample the minority class.
Used tree-based methods such as decision trees and random forest for classification problems. Both decision trees with adjusted weights and oversampling applied, the latter one gives a good balance of accuracy, recall, and f1 score.
