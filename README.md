# About the project

> This project aims to use data analytics to predict attrition and identify factors driving attrition. Using a dataset from a technology company, multiple machine learning models were built and tested. In addition, based on the results of these models, I provided strategic recommendations for the company to address attrition and improve employee retention.
>
> See my [Medium article](https://medium.com/@mailan_HOANG/predicting-attrition-using-logistic-regression-classification-tree-and-random-forest-d652a1f0d435) for more detailed write-up.

# Data

> I used a [dataset obtained from Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study) which contains data about 4,400 employees in a technology company and whether they have left the company (binary). The dataset includes a large number of variables about employee background (e.g., age, gender, education, marital status, years of experience, income), work requirements (e.g., work hours, overtime, training, business travel), employee satisfaction, and managers' evaluation of each employee's performance.
>
> The combined clean dataset is shared on this GitHub repository.

# Analyses

> After cleaning the data and splitting them into training and testing sets, I tested three types of machine learning models, including logistic regression, classification tree, and random forest. For each, I ran multiple models and evaluated them based on the following criteria:
>
> -   **Fit.** This is indicated by the significance of the independent variables or their impact on the dependent variable (attrition). For pairs of independent variables that are highly correlated, I only kept the variables with higher correlation with attrition to reduce multicollinearity issues.
>
> -   **Performance on the testing set.** I looked at accuracy, AUC (area under the receiver operating characteristic (ROC) Curve), and sensitivity. For this problem, it is important to prioritize sensitivity over specificity as the cost of false negatives (failing to capture employees who end up leaving) is often higher than the cost of false positives (predicting attrition for those who end up staying).
>
> -   **Business implications.** The models and variables selected should be interpretable. In addition, the thresholds used for predicting attrition should make business sense and can help guide management decisions.
>
> Comparing the three types of models against each other, it can be seen that the random forest model performed the best in terms of accuracy and sensitivity, with an area under the ROC curve close to 1. However, it lacks the interpretability and business implications offered by logistic regression and classification tree.

# Get in touch

> [\@Email](mailan.mlh@gmail.com)

> [\@LinkedIn](https://www.linkedin.com/in/mailan-hoang/)
