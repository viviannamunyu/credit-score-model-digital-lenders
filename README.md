# credit-score-model-digital-lenders
Machine learning credit scoring model using logistic regression to predict borrower repayment risk for digital lenders.

## Overview

This project developed a machine learning-based credit scorecard model to assess borrower creditworthiness and predict loan default risk for digital lenders.

Using Logistic Regression, Weight of Evidence (WOE), and Information Value (IV), the model generates transparent and explainable credit scores that support faster and data-driven lending decisions.

The project addresses a key challenge in digital lending: accurately assessing credit risk for applicants who may have limited credit history while maintaining model interpretability and regulatory transparency. 【1-d1f5e4】

## Problem Statement

Traditional credit assessment methods can be:

- Time-consuming
- Prone to human error
- Inconsistent across applicants
- Less effective in rapidly growing digital lending environments

This project aimed to develop a data-driven credit scorecard model that:

- Predicts loan repayment behavior
- Assigns credit scores to borrowers
- Classifies borrowers into risk categories
- Supports informed lending decisions

【1-d1f5e4】

## Objectives

### General Objective

Develop a credit scorecard model for digital lenders using Logistic Regression and Machine Learning techniques. 【1-d1f5e4】

### Specific Objectives

- Determine credit scores for loan applicants
- Rate customer creditworthiness based on credit scores
- Evaluate the effectiveness of the scoring model in managing credit risk

【1-d1f5e4】

## Dataset

**Source:** Kaggle Loan Prediction Dataset 【1-d1f5e4】

### Dataset Characteristics

- 614 loan application records
- Mix of categorical and numerical features
- Binary target variable representing loan approval status

### Key Features

- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Education Level
- Employment Status
- Dependents
- Marital Status
- Property Area

【1-d1f5e4】

## Methodology

This project followed the **CRISP-DM (Cross Industry Standard Process for Data Mining)** framework. 【1-d1f5e4】

### 1. Business Understanding

Identified the need for an interpretable and efficient credit scoring system for digital lenders.

### 2. Data Understanding

Conducted exploratory data analysis to understand:

- Loan approval patterns
- Income distributions
- Credit history trends
- Demographic influences on lending outcomes

### 3. Data Preparation

Performed:

- Missing value treatment
- Outlier handling
- Data transformation
- Feature engineering
- Variable selection

### 4. Modeling

Built a Logistic Regression model to classify applicants as:

- Defaulters
- Non-Defaulters

### 5. Evaluation

Evaluated model performance using:

- Accuracy
- Precision
- AUC-ROC
- Gini Coefficient
- KS Statistic

### 6. Credit Scorecard Development

Converted model outputs into interpretable credit scores and customer credit ratings.

【1-d1f5e4】

## Feature Engineering

To improve predictive performance, the following techniques were applied:

### Weight of Evidence (WOE)

WOE transformation was used to:

- Convert categorical variables into numerical values
- Improve model interpretability
- Maintain monotonic relationships between variables and default risk

### Information Value (IV)

Information Value was used to determine the predictive strength of variables and guide feature selection.

Variables with low predictive power were excluded from modeling.

### Binning

Continuous variables were grouped into bins to:

- Reduce noise
- Improve scorecard stability
- Enable credit score generation

【1-d1f5e4】

## Model Performance

The Logistic Regression model achieved the following results:

| Metric | Score |
|----------|----------|
| Accuracy | 77% |
| Precision | 97% |
| AUC-ROC | 0.8415 |
| Gini Coefficient | 0.6371 |
| KS Statistic | 0.6791 |

These results demonstrate strong discriminatory power between borrowers likely to default and those likely to repay their loans. 【1-d1f5e4】

## Key Findings

### Credit History Matters

Applicants with stronger credit histories had significantly higher approval rates. 【1-d1f5e4】

### Income Alone Is Not Sufficient

Higher income did not necessarily indicate lower default risk, highlighting the need for multi-factor credit assessment. 
