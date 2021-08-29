# Ensemble learning project
 Ensemble learning project for prediciting the success of a medical treatment, using feature-heavy tabular data. 
I used two ensemble algorithms – XGBoost and Random Forest – and calculated their mean score per row.
5-fold cross-fold validation was used to tune the hyperparameters of each algorithm.
In preprocessing, all data (both training and test) were one-hot encoded.
For the random forest algorithm, a simple imputer was used to handle missing values for categorical values the most frequent was chosen, and for numeric values the median was chosen).
The XGBoost algorithm can handle missing values on its own, and so for that algorithm the preprocessing did not include data imputation.

Resulting model predicted test data with 0.865 accuracy.
