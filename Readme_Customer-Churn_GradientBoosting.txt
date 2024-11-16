Customer Churn Prediction with Gradient Boosting
This repository demonstrates how to predict customer churn using Gradient Boosting algorithms, applied to a telecom customer dataset. The goal is to predict whether a customer will churn (leave the service) based on various attributes such as demographics, subscription details, and service usage patterns.

Dataset Overview:
The dataset contains 7043 entries and 21 columns, including both numerical and categorical features. It is used for binary classification, where the target variable is whether the customer has churned (Churn).

Features in the Dataset:
customerID: Unique identifier for each customer.
gender: Gender of the customer (e.g., Male, Female).
SeniorCitizen: Whether the customer is a senior citizen (1 for Yes, 0 for No).
Partner: Whether the customer has a partner (Yes, No).
Dependents: Whether the customer has dependents (Yes, No).
tenure: Length of time the customer has been with the company (in months).
PhoneService: Whether the customer has phone service (Yes, No).
MultipleLines: Whether the customer has multiple phone lines (Yes, No).
InternetService: Type of internet service the customer subscribes to (DSL, Fiber optic, No).
OnlineSecurity: Whether the customer has online security (Yes, No).
OnlineBackup: Whether the customer has online backup (Yes, No).
DeviceProtection: Whether the customer has device protection (Yes, No).
TechSupport: Whether the customer has tech support (Yes, No).
StreamingTV: Whether the customer has streaming TV (Yes, No).
StreamingMovies: Whether the customer has streaming movies (Yes, No).
Contract: Type of contract the customer has (Month-to-month, One year, Two year).
PaperlessBilling: Whether the customer has paperless billing (Yes, No).
PaymentMethod: Payment method used by the customer (Electronic check, Mailed check, Bank transfer, Credit card).
MonthlyCharges: Monthly charges for the customer’s service (float).
TotalCharges: Total charges the customer has paid (object, needs conversion to float).
Churn: Target variable (Yes if the customer has churned, No otherwise).

Goal:
The goal of this project is to build a Gradient Boosting model to predict customer churn, evaluate its performance, and optimize the model using techniques such as hyperparameter tuning.

Features:

Data Preprocessing:

Handling missing values.
Encoding categorical features (e.g., gender, contract type, etc.).
Converting the TotalCharges column to numeric after handling any issues with non-numeric values.
Scaling numerical features (e.g., MonthlyCharges, tenure).
Model Training: Implementing Gradient Boosting using libraries such as XGBoost, LightGBM, or custom Gradient Boosting implementations.
Hyperparameter Tuning: Optimizing the model using GridSearchCV or RandomizedSearchCV to fine-tune hyperparameters for better performance.
Model Evaluation: Evaluating the model using metrics such as accuracy, precision, recall, F1 score, ROC-AUC, and cross-validation.
Visualization: Visualizing model performance and feature importance to interpret the results.
