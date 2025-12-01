# Customer Credit Risk Model

Project Overview
This project develops an end-to-end machine learning model that predicts the probability that a customer will become delinquent or default on a credit obligation. The workflow includes data preparation, feature engineering, model training, evaluation, and model explainability.
This project reflects the analytical work performed by American Express Credit & Risk Analytics teams, who design, validate, and optimize underwriting and credit decisioning models.

Business Objective
A credit risk model supports several key objectives:
Assessing customer creditworthiness
Optimizing approval and decline decisions
Reducing portfolio exposure and losses
Enhancing risk-based segmentation
Supporting responsible lending strategies
This project simulates the development of a credit scoring model using borrower-level behavioral and financial features.

Methodology
The modeling pipeline includes:
Exploratory data analysis
Data cleaning and transformation
Feature engineering (utilization, income ratios, payment behavior)
Train/test split and cross-validation
Model training using Logistic Regression, Random Forest, and XGBoost
Model performance comparison using ROC-AUC and KS statistic
SHAP explainability to interpret risk drivers

Data Description
This project uses a combination of synthetic and publicly available credit datasets containing variables such as:
Credit utilization
Payment history
Loan amounts
Income and employment indicators
Age and demographic features
No personally identifiable or proprietary data is used.

Technical Skills Demonstrated
Python
Pandas, NumPy
Scikit-Learn, XGBoost
SHAP explainability
Data preprocessing and feature engineering
Model evaluation and interpretation
Jupyter Notebook workflow

Key Insights
The model identifies patterns commonly used in enterprise credit analytics, such as:
Higher utilization strongly correlates with increased default risk
Delinquency history is one of the most predictive features
Income-to-debt ratios influence probability of repayment
Certain demographic and behavioral segments show higher credit stability
These insights mirror real-world credit policy and decisioning processes.

Repository Structure
customer_credit_risk_model/
│── data/
│── notebooks/
│── src/
│── models/
│── reports/
│── README.md

Future Enhancements
Add model monitoring metrics
Deploy model with a real-time scoring API
Integrate challenger models for scorecard comparison
Build interactive risk dashboards











