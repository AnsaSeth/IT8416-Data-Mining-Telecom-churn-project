# Telecom Customer Churn Prediction
## IT8416 Data Mining — Group Project

## Project Overview
This project applies data mining techniques to predict customer churn 
in a telecom company. Using a dataset of 7,043 customers with 38 attributes, 
we built classification models to identify customers at risk of leaving.

## Problem Statement
Given telecom customer data including demographics, service usage, and 
billing information, predict whether a customer will churn, enabling 
targeted retention strategies.

## Dataset
- Source: Kaggle — Telecom Customer Churn Dataset
- Instances: 7,043 customers
- Attributes: 38 columns
- Target Variable: Customer Status (Churned / Stayed)

## Tools Used
- Altair AI Studio (RapidMiner) for data preprocessing and modelling
- Microsoft Word for report writing

## Project Tasks
- Task 1: Problem Statement and Definition
- Task 2: Dataset Selection and Exploration
- Task 3: Data Preprocessing (Missing values, Normalization, PCA)
- Task 4: Model Building (Decision Tree, Random Forest, Ensemble)
- Task 5: Model Evaluation
- Task 6: Inferences and Recommendations

## Models Built
| Model | Accuracy | F1-Score |
|---|---|---|
| Decision Tree | 78.99% | 59.78% |
| Random Forest | 83.68% | 66.08% |
| Ensemble (Bagging) | 76.51% | 27.25% |

## Best Model
Random Forest achieved the best overall performance with 83.68% accuracy 
and 66.08% F1-Score and is recommended for deployment.

## Key Findings
- Month-to-Month contract customers churn the most
- Higher monthly charges correlate with higher churn
- New customers with low tenure are at highest risk
- Fiber Optic internet users show higher churn rates

## Files in This Repository
- telecom_customer_churn.csv — Main dataset
- TASK3_DATA_PREPROCESSING.rmp — RapidMiner preprocessing process
- TASK4_DECISION_TREE.rmp — Decision Tree model
- TASK4_RANDOM_FOREST.rmp — Random Forest model
- TASK4_ENSEMBLE.rmp — Ensemble Bagging model
- IT8416_Project_Report.docx — Full project report

## Course Information
- Course: IT8416 Data Mining
- Institution: Bahrain Polytechnic
- Submission Date: 1st June 2026
