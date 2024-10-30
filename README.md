Introduction
   
In this notebook, we will predict whether a customer will churn (i.e., leave the company) in the past month, using data sourced from Kaggle. We will implement five algorithms utilizing the Scikit-learn library: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, and Support Vector Machine. This library also provides tools for data preprocessing and model performance evaluation.
Given that our dataset is imbalanced, which can skew the results, we will explore several methods to address this imbalance and mitigate overfitting. These methods include hyperparameter tuning, the use of balanced class weights, and the application of the SMOTE-ENN technique. Our primary optimization objective will be the area under the ROC curve, while we will also track accuracy, precision and recall throughout each experiment.
.
