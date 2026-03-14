# Credit Risk Prediction using Machine Learning
Overview

This project develops machine learning models to predict credit default risk using customer financial behavior and repayment history.

The objective is to help financial institutions identify high-risk borrowers early, reduce credit losses, and improve credit approval decisions.

Using historical loan and repayment data, multiple machine learning models were trained and evaluated to identify the most accurate predictive approach.

# Dataset

The dataset contains financial behavior variables related to credit usage and repayment patterns, including:

Repayment history

Credit account status

Debt recovery indicators

Merchant category activity

Payment span behavior

Account balances and transaction activity

Sample dataset included in this repository:

data/credit_risk_sample.csv
# Project Workflow

The project follows a standard machine learning pipeline:

Data Cleaning and Preprocessing

Feature Engineering

Exploratory Data Analysis (EDA)

Model Training

Model Evaluation

Feature Importance Analysis

Machine Learning Models Used

# The following models were trained and compared:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

AdaBoost

Random Forest provided the best predictive performance.



## Exploratory Data Analysis

## EDA Distribution

![Default Distribution](images/eda_distribution.png)

## Correlation heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

## ROC Curve

![ROC Curve](images/roc_curve.png)

## Feature Important

![Feature Importance](images/feature_importance.png)

EDA helped identify relationships between repayment behavior and default risk.


# Model Evaluation Results

Random Forest produced the best results.

Performance metrics:

| Metric          | Value  |
| --------------- | ------ |
| ROC-AUC Score   | 0.833  |
| True Negatives  | 29,594 |
| False Positives | 14     |
| False Negatives | 357    |
| True Positives  | 29     |


The model demonstrates strong ability to distinguish between default and non-default borrowers.

# Key Predictive Features


| Feature | Description |
|------|------|
| Time since last financial activity | Measures recent financial engagement of the borrower |
| Customer age | Indicates financial maturity and credit stability |
| Average payment span | Average time taken to settle invoices |
| Merchant category behavior | Spending patterns across merchant groups |
| Incoming debt vs paid ratio | Balance between incoming liabilities and repayments |
| Invoice payment history | Historical pattern of invoice payments |


## How to Run the Project

Follow these steps to reproduce the analysis and model results.

### 1. Clone the repository

```bash
git clone https://github.com/rwatave/credit-risk-prediction-ml.git
cd credit-risk-prediction-ml

## 2. Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

## 3. Open the notebook
notebook/Credit_risk_model_Capstone_GL.ipynb

## 4. Run the notebook

Run all cells to reproduce:

data preprocessing

exploratory data analysis

model training

model evaluation


## Project Structure

credit-risk-prediction-ml
│
├── notebook
│   └── Credit_risk_model_Capstone_GL.ipynb
│
├── images
│   ├── eda_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── data
│   └── credit_risk_sample.csv
│
├── report
│   └── Final_Business_Report.pdf
│
├── requirements.txt
└── README.md


Author

Rohan Watave  
MS in Data Analytics — Clark University
