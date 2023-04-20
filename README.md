# Welcome to the prediction of the severity of lung cancer

## ABOUT

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which make use of mostly categorical data to predict the severity of lung cancer by using a [lung cancer dataset](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b867f48eec8569710eb28fc9530ce080948a36bf/cancer%20patient%20data%20sets.csv) from [Kaggle](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link) . For detailed walk-through, please read the source codes in the following order:

1. [Lung Dataset Cleaning and Preparation](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b1cc03041579bd5bad839a664623eefa3e77b987/Lung%20Dataset%20Cleaning%20and%20Preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b1cc03041579bd5bad839a664623eefa3e77b987/Exploratory%20Data%20Analysis.ipynb)
3. [Machine Learning Model](https://github.com/XiaozKang/Lung-Cancer-Prediction/blob/b34ed2c46780f28cff58b2cf13d245b267cd9d2b/Machine%20Learning%20Model.ipynb)

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
1. The importance of Data Exploration and Visualisation
    - Identify patterns, trends, and anomalies in the dataset
    - Understand data's distribution and relationship between each variables
2. How to Detect and Remove Outliers
    - Identify outliers using visualisation methods like boxplot
    - Remove outliers using IQR method
3. How to Select the Best Features for Predicting our Target Variable
    - Splitting of data types: Continuous, Ordinal, Categorical
    - Using Pearson correlation to narrow down Continuous features
    - Using Chi-Square Test to narrow down to the top best Ordinal and Categorical features
    - Using Logistic Regression Model to evaluate the narrowed down features to ensure accuracy for our main model
4. How to Tune Hyperparameter for Logistic Regression Model
    - We have learned about hyperparameters such as regularization strength and penalty in Logistic Regression.
    - Using the GridSearchCV technique to fine tune the hyperparameters to ensure optimality for our selected features.
5. Applying and Evaluating Multi Class Decision Tree
    - We learned that Multi Class Decision Tree model is useful for predicting categorical data with more than 2 unqiue categories.
    - Using Confusion Matrix, Classification Report, and Accuracy Scores as metrics to evaluate our models.
6. Predicting Outcomes for New Data
    - We learned how to predict new data using our trained machine learning model using user input.
7. Logistic Regression from Sklearn
8. The use of Chi-squared function
9. Function of Github
10. More efficient use of Python

## References

- <https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link>
- <https://www.scribbr.com/statistics/chi-square-distributions/>
- <https://towardsdatascience.com/how-is-logistic-regression-used-as-a-classification-algorithm-51eaf0d01a78>
- <https://stackoverflow.com/questions/38077190/how-to-increase-the-model-accuracy-of-logistic-regression-in-scikit-python>
- <https://scikit-learn.org/stable/modules/grid_search.html>
- <https://scikit-learn.org/stable/modules/multiclass.html>
- <https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html>
- <https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier>
