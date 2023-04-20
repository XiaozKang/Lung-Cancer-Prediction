# Welcome to the prediction of the severity of lung cancer

## ABOUT

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which make use of mostly categorical data to predict the severity of lung cancer by using a [lung cancer dataset](cancer patient data sets.csv) from [Kaggle](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link) . For detailed walk-through, please read the source codes in the following order:

1. [Lung Dataset Cleaning and Preparation](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b1cc03041579bd5bad839a664623eefa3e77b987/Lung%20Dataset%20Cleaning%20and%20Preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b1cc03041579bd5bad839a664623eefa3e77b987/Exploratory%20Data%20Analysis.ipynb)
3. [Machine Learning Model](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/4ed883d9a5f10db8424d6a09080b65aeb2b3217c/Machine%20Learning%20Model%20.ipynb)

## Contributors

- @XiaozKang - Data Cleaning and Preparation, Exploratory Data Analysis, Machine Learning Model
- @raccocoder - Data Cleaning and Preparation, Exploratory Data Analysis, Machine Learning Model
- @Lootty - Data Cleaning and Preparation, Exploratory Data Analysis, Machine Learning Model

## Problem Definition

- Are we able to predict the severity of a lung cancer patient?
- Which model can be used to choose the predictors and predict it?

## Models Used

1. Chi-squared Function
2. Logistic Regression
3. Multi Class Decision Tree

## Conclusion

- Age as the only numerical data, has a weak relation with respect to the severity of lung cancer
- Linear Regression is meant for numerical data, while Logisitic regression is meant for categorical ones
- The top 10 predictors we chose play crucial roles in predicting the severity of lung cancer accurately
- The predictors with higher chi-squared value suggest a stronger relation
- Classification accuracy is very high (~0.95)
- Hence, it is considered to be very successful when it comes to predicting severity of lung cancer

## What did we learn from this project?

- Applying multi class decision tree for categorical data with more than 2 unqiue categories
- Logistic Regression from Sklearn
- The use of Chi-squared function
- Function of Github
- More efficient use of Python

## References

- <https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link>
- <https://www.scribbr.com/statistics/chi-square-distributions/>
- <https://scikit-learn.org/stable/modules/multiclass.html>
- <https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html>
