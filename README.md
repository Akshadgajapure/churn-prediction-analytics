# 📊 Customer Churn Prediction & Analytics

An end-to-end **Customer Churn Prediction and Business Intelligence** project that combines **SQL, Python Machine Learning, and Power BI** to analyze customer behavior, identify churn drivers, and predict customers at risk of leaving.

The project demonstrates how data analytics and machine learning can help telecom and subscription-based businesses reduce customer churn through data-driven decision making.

---

## 📌 Project Objective

Customer churn is one of the biggest challenges for subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to:

- Analyze customer behavior and churn patterns
- Identify key factors influencing customer churn
- Build a Machine Learning model to predict churn
- Visualize business insights using interactive Power BI dashboards
- Identify customers at high risk for targeted retention campaigns

---

## 🏗️ Project Architecture

```
                Raw Customer Data
                       │
                       ▼
          SQL Data Extraction & Cleaning
                       │
                       ▼
        Data Preprocessing (Python)
                       │
                       ▼
             Feature Engineering
                       │
                       ▼
      Random Forest Classification Model
                       │
                       ▼
            Model Performance Evaluation
                       │
                       ▼
             Churn Probability Prediction
                       │
                       ▼
          Power BI Business Dashboards
```

---

## 🛠️ Tech Stack

### Programming & Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier

### Database
- SQL Server
- SQL Queries

### Business Intelligence
- Power BI

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

## 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── Data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── SQL/
│   └── data_extraction.sql
│
├── notebooks/
│   ├── Data_Preprocessing.ipynb
│   ├── Model_Training.ipynb
│   └── Model_Evaluation.ipynb
│
├── PowerBI/
│   └── Customer_Churn_Dashboard.pbix
│
├── Images/
│   ├── dashboard1.png
│   └── dashboard2.png
│
├── model.pkl
│
├── requirements.txt
│
└── README.md
```

---

# 🔄 Machine Learning Pipeline

## 1. Data Preprocessing

- Missing value handling
- Duplicate removal
- Data cleaning
- Feature transformation
- Encoding categorical variables

---

## 2. Feature Engineering

The model uses several customer attributes, including:

- Customer demographics
- Tenure
- Internet service
- Contract type
- Payment method
- Monthly charges
- Total charges
- Online security
- Tech support
- Streaming services

---

## 3. Model Training

A **Random Forest Classifier** was trained to classify customers into:

- Churn
- Non-Churn

Random Forest was selected because it:

- Handles mixed feature types
- Reduces overfitting
- Provides high predictive accuracy
- Captures non-linear relationships

---

## 4. Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | 85% |
| Precision | 80% |
| Recall | 76% |
| F1 Score | 78% |
| ROC-AUC | **0.916** |

*(Update the metrics according to your final results if different.)*

---

# 📈 Power BI Dashboards

The project includes two interactive dashboards.

---

## Dashboard 1 – Customer Churn Analysis

Provides an overview of historical churn patterns.

### Key KPIs

- Total Customers
- New Joiners
- Total Churn
- Churn Rate

### Visualizations

- Churn by Gender
- Churn by Age Group
- Churn by State
- Churn by Internet Service
- Churn by Payment Method
- Churn by Contract Type
- Churn by Tenure
- Churn by Services Used

This dashboard helps identify the primary drivers behind customer churn.

---

## Dashboard 2 – Customer Churn Prediction

Displays customers predicted to churn using the trained machine learning model.

### Key Insights

- Predicted Churn Profile
- State-wise Risk Distribution
- Age Group Analysis
- Contract Type Analysis
- Customer Risk Segmentation

### Customer At Risk Table

A dedicated table lists customers with a high probability of churn, enabling businesses to take proactive retention actions.

---

# 💡 Business Insights

The analysis revealed several important findings:

- Customers with **Month-to-Month contracts** exhibit the highest churn rate.
- **Fiber Optic Internet** users are more likely to churn than DSL users.
- Customers with **short tenure** are at greater risk of leaving.
- Certain states have significantly higher churn concentrations.
- Customers lacking services such as **Online Security** and **Tech Support** tend to churn more frequently.

These insights can support targeted marketing campaigns and customer retention strategies.

---

# 📊 Business Impact

The project enables organizations to:

- Reduce customer churn
- Improve customer retention
- Identify high-risk customers
- Optimize marketing campaigns
- Increase customer lifetime value
- Support data-driven business decisions

---

# 🚀 Future Improvements

Potential enhancements include:

- Hyperparameter tuning
- XGBoost and LightGBM implementation
- Model deployment using Streamlit or Flask
- Real-time churn prediction API
- Automated model retraining pipeline
- Explainable AI using SHAP values
- Customer retention recommendation engine

---

# ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

### Open Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop**.

---

# 📸 Dashboard Preview

## Churn Analysis Dashboard

> *(Add screenshot here)*

```
Images/dashboard1.png
```

---

## Churn Prediction Dashboard

> *(Add screenshot here)*

```
Images/dashboard2.png
```

---

# 📚 Skills Demonstrated

- SQL
- Python
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Random Forest Classification
- Model Evaluation
- Power BI
- Data Visualization
- Business Intelligence

---

# 👨‍💻 Author

**Akshad Gajapure**

Chemical Engineering Undergraduate | NIT Raipur

Interested in:
- Data Analytics
- Machine Learning
- Business Intelligence
- Artificial Intelligence

GitHub: https://github.com/Akshadgajapure

---

## ⭐ If you found this project helpful, consider giving it a star!
