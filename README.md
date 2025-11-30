**#Unified Multi-Risk Financial Dataset (Credit, Fraud & AML)**

This directory contains a synthetic but realistic financial dataset designed for machine learning research across credit risk prediction, fraud detection, and AML (Anti-Money Laundering) suspicious activity analysis. The dataset reflects common structures used in Canadian retail banking environments and is appropriate for analytics training, academic work, and prototyping multi-risk scoring models.

📁 Dataset Files
1. customers_updated.csv

Contains customer-level demographic and financial attributes.

2. accounts_updated.csv

Contains account-level information linked to each customer, including credit limits, balances, and delinquency indicators.

3. transactions_updated.csv

Contains transaction-level activity records including channels, amounts, merchant categories, and behavioural patterns relevant for fraud and AML modeling.

4. merged_MultiRiskDatasetGB.csv

A consolidated dataset combining customers, accounts, and transactions into a single modeling-ready table.
This file is used in the machine learning notebooks for unified risk classification.

📌 Dataset Structure
Customer-Level Features

Customer ID

Age

Gender

Annual income

Employment status

Province

Account tenure

Mortgage indicator

Risk segment (if applicable)

Account-Level Features

Account ID

Account type (chequing, savings, credit card, etc.)

Credit limit

Current balance

Delinquency flags (30/60 days)

Opening date

Utilization indicators

Transaction-Level Features

Transaction ID

Amount

Transaction type

Channel (POS, ATM, online, mobile)

Merchant category

International flag

Device ID

Timestamp (date/time fields)

Night-time or abnormal behaviour flags

Target Variables

Depending on use case:

credit_default_flag

is_fraud

is_aml_suspicious

📌 Intended Use Cases

This dataset supports advanced analytics and machine learning tasks such as:

Credit default prediction

Fraud anomaly detection

AML suspicious transaction classification

Imbalanced classification techniques

Behavioural segmentation

Feature engineering and model governance

End-to-end financial risk modeling workflows

📌 Recommended Modeling Approaches

The dataset is structured to work effectively with:

Logistic Regression

Interpretable and regulator-friendly

Suitable for credit scoring and baseline AML/fraud models

XGBoost

High predictive accuracy

Handles nonlinear patterns and imbalanced data

Ideal for fraud detection and AML risk scoring

📌 Notes

All data is synthetic and created solely for research, learning, and prototyping.

No real customer information is included.

Not intended for production, commercial, or regulatory use.
