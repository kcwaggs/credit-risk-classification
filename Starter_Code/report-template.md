# Module 12 Report Template

## Overview of the Analysis

The analysis aimed to develop machine learning models for predicting loan statuses based on financial information. The dataset contained various features related to loan applicants, such as credit score, annual income, debt-to-income ratio, etc. The target variable was the loan status, which indicated whether a loan was healthy (0) or high-risk (1).

The stages of the machine learning process involved:
    1. Data preprocessing: Handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
    2. Model training: Training different machine learning algorithms such as Logistic Regression, Random Forest, etc., on the training data.
    3. Model evaluation: Evaluating the performance of each model using metrics like accuracy, precision, and recall.

## Results

Logistic Regression Model:
    Accuracy: 0.99
    Precision:
        Healthy Loans (0): 1.00
        High-Risk Loans (1): 0.85
    Recall:
        Healthy Loans (0): 0.99
        High-Risk Loans (1): 0.91

## Summary

The Logistic Regression model performed exceptionally well in predicting both healthy and high-risk loans. It achieved high accuracy and demonstrated high precision and recall for both classes. The model's performance is crucial for this problem as it is equally important to correctly identify both healthy and high-risk loans to manage the lending risk effectively.

Considering the high performance and interpretability of the Logistic Regression model, it is recommended for deployment in practical lending scenarios. However, it's essential to continuously monitor and update the model as the lending landscape evolves.
