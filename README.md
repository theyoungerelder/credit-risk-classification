# credit-risk-classification

# Module 20 Credit Risk Report

## Overview of the Analysis

* **Purpose of the analysis** - Assess Logistic Regression's ability to predict healthy (0) and high-risk (1) loans using the original or resampled dataset.
* **The Dataset** - Contains info on 77,536 loans with loan attributes and loan_status as the target.

* **Stages of the Machine Learning Process** 
Data Preparation
Feature-Label Split
Train-Test Split
Model Import (LogisticRegression)
Model Instantiation, Fitting, and Prediction
Evaluation using accuracy, precision, and recall.
    
* **Machine Learning Methods Utilized** - 

Main Model: LogisticRegression
Supporting Functions: 
- train_test_split, 
- confusion_matrix,
- classification_report

## Results

Model 1 - Logistic Regression:

- Accuracy: 0.99
- Precision (Class 0: 1.00, Class 1: 0.85)
- Recall (Class 0: 0.99, Class 1: 0.91)


## Summary

The Logistic Regression model performed well, especially for Class 0 (healthy loans). For Class 1 (high-risk loans), it had lower precision (0.84) but good recall (0.91), indicating occasional false positives.

In conclusion, the model shows promise for loan health prediction but requires further testing on different datasets before implementation.

