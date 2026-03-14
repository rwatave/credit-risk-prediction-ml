# Credit Risk Prediction using Machine Learning

## Problem
Financial institutions need to predict whether customers will default on credit card payments.  
This project builds machine learning models to identify high-risk borrowers using financial behavioral data.

## Dataset
The dataset contains ~100,000 financial records including:

- payment history
- credit utilization
- account balances
- demographic attributes

A sample dataset is included in the repository.

## Machine Learning Models
- Logistic Regression
- Random Forest

## Model Performance
ROC-AUC Score: **0.86**

## Tools Used
Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  

## Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Training
5. Model Evaluation

## Repository Structure


credit-risk-prediction-ml/
│
├── notebooks/
│   └── credit_risk_model.ipynb
│
├── data/
│   └── credit_sample.csv
│
├── images/
│   ├── correlation_heatmap.png
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│
└── requirements.txt
