# BostonHousePrediction


Instruction

Boston Housing Dataset
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. It has been used extensively throughout the Data Science World to benchmark algorithms.

Note:
Attention, learners. Please be aware that the Boston dataset has been eliminated from prior versions of scikit learn due to ethical considerations. If you wish to access the Boston dataset, we suggest installing an older version of scikit learn. You can accomplish this by executing the following command: "pip install scikit-learn==1.1.3."

The Data
The target of this Assignment is to be able to predict the target variable (Median house value), given the other input variables.

Column	Description:

Columns:
- **CRIM: ** Per capita crime rate by town
- **ZN: ** Proportion of residential land zoned for lots over 25,000 sq. ft
- **INDUS: ** Proportion of non-retail business acres per town
- **CHAS : ** Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX: ** Nitric oxide concentration (parts per 10 million)
- **RM: ** Average number of rooms per dwelling
- **AGE: ** Proportion of owner-occupied units built prior to 1940
- **DIS: ** Weighted distances to five Boston employment centers
- **RAD: ** Index of accessibility to radial highways
- **PTRATIO: ** Pupil-teacher ratio by town
- **B: ** 1000(Bk — 0.63)², where Bk is the proportion of [people of African American descent] by town
- **LSTAT: ** Percentage of lower status of the population
- **MEDV: ** Median value of owner-occupied homes in $1000s
The target of this Assignment is to be able to predict the target variable (Median house value), given the other input variables




Conclusion:

I have built 6 regression models using Boston Housing Dataset.

These are linear, polynomial, ridge, lasso, decision tree and random forest regression.

Then measured and visualized the performance of the models.

Cross Validation Score is greater for Random Forest Regression:

R2 Score (training) is greater for Decision Tree Regression:

Whereas R2 Score (test) is greater for Lasso Regression as well as Ridge Regression:

RMSE is greater for Decision Tree and Polynomial Regression (2nd) in comparison between different models.





