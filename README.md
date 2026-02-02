# Fraud Detection using Machine Learning

This project focuses on detecting fraudulent financial transactions using machine learning techniques. The dataset contains over 6.3 million transactions and is highly imbalanced, requiring careful feature engineering and evaluation strategies.

## Problem Statement
The goal is to build a fraud detection model and derive actionable business insights to prevent fraudulent activities in a financial system.

## Dataset
- Transactions: 6,362,620
- Features: Transaction details including amount, balances, transaction type, and time
- Target: `isFraud` (1 = Fraud, 0 = Legitimate)

## Approach
- Data cleaning and validation
- Feature engineering (balance differences, log-transformed amounts, time features)
- Baseline model: Logistic Regression
- Final model: Random Forest
- Evaluation metrics: Precision, Recall, F1-score, ROC-AUC

## Key Insights
- Balance-related features are the strongest indicators of fraud
- Fraud typically occurs through TRANSFER followed by CASH_OUT transactions
- Machine learning models outperform rule-based fraud detection systems

## Files
- `notebooks/Fraud_Detection_Accredian.ipynb`: Full analysis and modeling
- `data/fraud_data.csv`: Transaction dataset
- `data/data_dictionary.txt`: Feature descriptions

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Google Colab

## Author
Abhishek Raj
