# 🧠 Credit Scoring Model

## 📌 Objective
This project aims to build a predictive machine learning model that assesses an individual's *creditworthiness* using historical financial data. By analyzing features such as income, outstanding debts, and payment history, the model classifies individuals as either *creditworthy (good)* or *non-creditworthy (risky)*.

## 🛠 Problem Statement
Lenders and financial institutions need reliable tools to evaluate the risk of loan default. This model helps in making data-driven decisions by predicting the probability of default based on historical financial indicators.

### Key Features:
- income: Annual income of the individual
- debts: Outstanding debt amount
- payment_history: Indicator of timely payments
- missed_payments: Number of missed payments
- creditworthy: Target variable (1 = Yes, 0 = No)

## 🧪 Approach

The task is treated as a *binary classification problem*. The following supervised learning algorithms are implemented:

- ✅ Logistic Regression  
- ✅ Random Forest Classifier  

The data is preprocessed using scaling techniques, and models are evaluated using both *threshold-based* and *probability-based* performance metrics.

## ⚙ Tech Stack

- *Language*: Python
- *Libraries*:
  - pandas, numpy – Data manipulation
  - scikit-learn – ML algorithms, model evaluation
  - matplotlib, seaborn – Visualization

## 📈 Evaluation Metrics

- *Confusion Matrix*
- *Precision, Recall, F1-Score*
- *ROC-AUC Score*
- *ROC Curve Visualization*
