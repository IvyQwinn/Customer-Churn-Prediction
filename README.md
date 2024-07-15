# Customer Churn Prediction

## Project Description
This project focuses on predicting customer churn using various machine learning models. The dataset includes customer information such as demographics, account details, and services used. The goal is to build and evaluate models to accurately predict whether a customer will churn, helping businesses take proactive measures to retain customers.

## Dataset
The dataset contains features like customer demographics, account details, and the services used by the customers. The target variable is whether the customer churned or not.

## Models Used
We have implemented and evaluated the following machine learning models:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost

## Evaluation Metrics
The models were evaluated using the following metrics:
- **Accuracy:** The ratio of correctly predicted instances to the total instances.
- **Precision:** The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall:** The ratio of correctly predicted positive observations to the all observations in actual class.
- **F1 Score:** The weighted average of Precision and Recall.

## Results
The performance of each model is summarized below:

| Model                | Accuracy | Precision | Recall  | F1 Score |
|----------------------|----------|-----------|---------|----------|
| Logistic Regression  | 0.859070 | 0.620690  | 0.178218| 0.276923 |
| Decision Tree        | 0.884558 | 0.630435  | 0.574257| 0.601036 |
| Random Forest        | 0.926537 | 0.861111  | 0.613861| 0.716763 |
| XGBoost              | 0.923538 | 0.837838  | 0.613861| 0.708571 |
