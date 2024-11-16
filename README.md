Customer Churn Prediction with Gradient Boosting

This repository demonstrates how to predict customer churn using Gradient Boosting algorithms, applied to a telecom customer dataset. The goal is to predict whether a customer will churn (leave the service) based on various attributes such as demographics, subscription details, and service usage patterns.

Dataset Overview:

The dataset contains 7043 entries and 21 columns, including both numerical and categorical features. It is used for binary classification, where the target variable is whether the customer has churned (Churn).

Features in the Dataset:
1. customerID: Unique identifier for each customer.
2. gender: Gender of the customer (e.g., Male, Female).
3. eniorCitizen: Whether the customer is a senior citizen (1 for Yes, 0 for No).
4. Partner: Whether the customer has a partner (Yes, No).
5. Dependents: Whether the customer has dependents (Yes, No).
6. tenure: Length of time the customer has been with the company (in months).
7. PhoneService: Whether the customer has phone service (Yes, No).
8. MultipleLines: Whether the customer has multiple phone lines (Yes, No).
9. InternetService: Type of internet service the customer subscribes to (DSL, Fiber optic, No).
10. OnlineSecurity: Whether the customer has online security (Yes, No).
11. OnlineBackup: Whether the customer has online backup (Yes, No).
12. DeviceProtection: Whether the customer has device protection (Yes, No).
13. TechSupport: Whether the customer has tech support (Yes, No).
14. StreamingTV: Whether the customer has streaming TV (Yes, No).
15. StreamingMovies: Whether the customer has streaming movies (Yes, No).
16. Contract: Type of contract the customer has (Month-to-month, One year, Two year).
17. PaperlessBilling: Whether the customer has paperless billing (Yes, No).
18. PaymentMethod: Payment method used by the customer (Electronic check, Mailed check, Bank transfer, Credit card).
19. MonthlyCharges: Monthly charges for the customer’s service (float).
20. TotalCharges: Total charges the customer has paid (object, needs conversion to float).
21. Churn: Target variable (Yes if the customer has churned, No otherwise).

Goal:
The goal of this project is to build a Gradient Boosting model to predict customer churn, evaluate its performance, and optimize the model using techniques such as hyperparameter tuning.

Features:

Data Preprocessing:

1. Handling missing values.
2. Encoding categorical features (e.g., gender, contract type, etc.).
3. Converting the TotalCharges column to numeric after handling any issues with non-numeric values.
4. Scaling numerical features (e.g., MonthlyCharges, tenure).
5. Model Training: Implementing Gradient Boosting using libraries such as XGBoost, LightGBM, or custom Gradient Boosting implementations.
6. Hyperparameter Tuning: Optimizing the model using GridSearchCV or RandomizedSearchCV to fine-tune hyperparameters for better performance.
7. Model Evaluation: Evaluating the model using metrics such as accuracy, precision, recall, F1 score, ROC-AUC, and cross-validation.
8. Visualization: Visualizing model performance and feature importance to interpret the results.
