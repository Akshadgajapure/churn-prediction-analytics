# Customer Churn Prediction & Analytics
An end-to-end Customer Churn Prediction and Business Intelligence project that combines SQL, Machine Learning (Python), and Power BI dashboards to analyze churn patterns and identify customers at risk of leaving.
This project demonstrates how data analytics and machine learning can help businesses understand churn drivers and proactively retain customers.

# Project Objective
Customer churn is a critical problem for telecom and subscription-based businesses. Losing customers leads to revenue loss and higher acquisition costs.
The objective of this project is to:
1)Analyze customer behavior and churn patterns
2)Identify key factors contributing to churn
3)Build a machine learning model to predict churn
4)Visualize insights using interactive Power BI dashboards
5)Identify customers at risk of leaving

# Project Architecture
Raw Customer Data
       ↓
SQL Data Extraction & Cleaning
       ↓
Data Preprocessing (Python)
       ↓
Feature Engineering
       ↓
Machine Learning Model (Random Forest)
       ↓
Model Evaluation
       ↓
Churn Prediction
       ↓
Power BI Dashboard Visualization

# Tech Stack
1)Programming & Data Processing
Python,
Pandas,
NumPy,
Machine Learning,
Scikit-learn,
Random Forest Classifier

2)Data Extraction
SQL Server,
SQL queries for data preparation

3)Vsualization
Power BI

4)Tools
VS Code,
Git,
GitHub,
Jupyter Notebook


# Machine Learning Pipeline
The churn prediction model includes the following steps:

1. Data Preprocessing
Handling missing values
Encoding categorical variables
Feature transformation
Data cleaning

3. Feature Engineering
Key features used for prediction include:
Customer demographics
Service usage
Contract type
Billing information
Tenure
Internet services

4. Model Training
A Random Forest Classifier was used to train the churn prediction model.

5. Model Evaluation
The model performance was evaluated using:
Confusion Matrix
Precision
Recal
F1 Score
ROC-AUC Score


# Power BI Dashboards
The project includes two dashboards.
1. Churn Analysis Dashboard
This dashboard focuses on understanding churn behavior.
Key KPIs
-Total Customers
-New Joiners
-Total Churn
-Churn Rate

Analysis Includes
Churn by Gender
Churn by Age Group
Churn by State
Churn by Internet Typ
Churn by Payment Method
Churn by Contract Type
Churn by Tenure Group
Churn by Services Used

This helps identify key churn drivers.

2. Churn Prediction Dashboard
This dashboard focuses on predicting customers who may churn in the future.
Key Insights
-Predicted churner profile
-State-wise churn distribution
-Age group churn patterns
-Contract type churn patterns
-Customer risk segmentation

Key Feature

Customers predicted to churn are listed in a Customers at Risk table for targeted retention strategies.


# Example Business Insights
Some insights derived from the analysis include:
1)Customers with month-to-month contracts have the highest churn rate
2)Fiber optic internet users churn more frequently
3)Customers with short tenure are more likely to churn
4)Certain states show higher churn concentration
5)These insights help businesses design targeted retention campaigns.
