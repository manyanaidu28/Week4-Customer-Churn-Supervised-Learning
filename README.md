# Week 4 - Customer Churn Supervised Learning

## Project Overview

This project focuses on predicting customer churn using supervised machine learning techniques. The IBM Telco Customer Churn dataset was used to analyze customer behavior and build predictive models that can identify customers who are likely to leave the service.

## Objectives

- Preprocess and prepare customer churn data
- Select relevant numerical features
- Split the dataset into training and testing sets
- Apply feature scaling
- Build Logistic Regression and Random Forest models
- Evaluate model performance using multiple metrics
- Compare the performance of both models
- Identify important features influencing customer churn

## Dataset

Dataset: IBM Telco Customer Churn Dataset

The dataset contains 7,043 customer records and 21 columns, including customer demographics, services, account information, and churn status.

## Machine Learning Models

### 1. Logistic Regression
Used as a baseline classification model for predicting whether a customer will churn.

### 2. Random Forest
An ensemble learning model used to capture nonlinear relationships and evaluate feature importance.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC
- 5-Fold Cross-Validation

## Results

Logistic Regression achieved better overall performance than Random Forest.

- Logistic Regression Test Accuracy: 78.42%
- Logistic Regression Cross-Validation Accuracy: 79.11%
- Logistic Regression ROC-AUC: 0.82
- Random Forest Test Accuracy: 76.37%
- Random Forest Cross-Validation Accuracy: 76.23%
- Random Forest ROC-AUC: 0.77

## Key Findings

- Logistic Regression performed better than Random Forest on the selected features.
- Monthly Charges and Total Charges were among the most important predictive features.
- ROC-AUC results indicate that Logistic Regression provided stronger discrimination between churned and non-churned customers.
- The models can help identify customers who are more likely to churn.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Repository Contents

- `Week4_Customer_Churn_Supervised_Learning.ipynb` - Complete machine learning notebook
- `README.md` - Project documentation

## Conclusion

This project demonstrates how supervised machine learning can be applied to customer churn prediction. Logistic Regression provided the best performance among the tested models and can serve as a useful baseline for identifying customers at higher risk of churn.
