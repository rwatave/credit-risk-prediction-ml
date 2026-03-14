# Credit Risk Prediction using Machine Learning

## Overview
This project builds machine learning models to predict **credit default risk** using financial behavior and repayment history data.

The goal is to help financial institutions identify high-risk borrowers and improve credit decision-making.

---

## Dataset
The dataset contains financial account behavior variables including:

- repayment history
- credit account status
- debt recovery metrics
- merchant category activity
- payment span
- account balances

Sample dataset included in:


---

## Project Workflow

1. Data Cleaning
2. Feature Engineering
3. Exploratory Data Analysis
4. Machine Learning Modeling
5. Model Evaluation

Models used:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost

---

## Exploratory Data Analysis

### Default Distribution
![Default Distribution](images/eda_distribution.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

---

## Model Performance

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve
![ROC Curve](images/roc_curve.png)

### Feature Importance
![Feature Importance](images/feature_importance.png)

---

## Results

Best performing model: **Random Forest**

Key predictive features:

- repayment_ratio
- recovery_debt
- worst_status_max
- avg_payment_span
- sum_paid_inv_0_12m

The model achieved strong predictive performance with high ROC-AUC.

---

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-Learn  
Matplotlib  
Seaborn  

---

## Notebook

Full code available in:


---

## Business Impact

This model can help lenders:

- reduce credit losses
- identify high-risk customers
- improve loan approval decisions
- optimize risk-based pricing
