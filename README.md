# fraud-detection-analytics
# Beyond the Threshold: An End-to-End Fraud Detection Pipeline Using Machine Learning on Imbalanced Credit Card Data

MSc Business Analytics Dissertation — Queen's Business School
Abdul Banire | 40490950

## Overview
This project builds an end-to-end machine learning pipeline to detect
fraudulent credit card transactions in the presence of severe class
imbalance (492 fraud cases out of 284,807 transactions, ~0.172%).

## Pipeline
- **Data ingestion**: PostgreSQL relational database
- **EDA**: class distribution, transaction amount analysis, correlation matrix
- **Class imbalance handling**: SMOTE (training set only, to avoid data leakage)
- **Models**: Logistic Regression, Random Forest, XGBoost
- **Evaluation**: Precision, Recall, F1, ROC-AUC, PR-AUC, threshold sensitivity analysis
- **Interpretability**: SHAP
- **Dashboard**: Power BI / Tableau (business-facing risk intelligence)

## Dataset
[Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
— originally published by the Université Libre de Bruxelles (ULB).

## Repository structure
├── data/              # (not included — see Kaggle link above)
├── notebooks/         # EDA and modelling notebooks
├── figs/               # Generated figures
├── Appendix_2_Code.py  # Full pipeline script
└── README.md
