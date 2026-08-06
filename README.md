# 📊 Customer Churn Prediction & Analytics

An end-to-end Customer Churn Prediction project that combines **SQL**, **Python**, **Machine Learning**, and **Power BI** to analyze customer behavior, predict customer churn, and provide actionable business insights.

---

## 🚀 Project Overview

Customer churn is a major challenge for subscription-based businesses. Losing existing customers reduces revenue and increases acquisition costs.

This project demonstrates how data analytics and machine learning can help businesses identify customers likely to churn and support proactive retention strategies.

---

## 🎯 Objectives

- Analyze historical customer churn patterns
- Identify important churn drivers
- Build a Random Forest model to predict churn
- Visualize business insights using Power BI
- Identify customers at risk of leaving

---

# 🏗️ Project Workflow

```
Customer Data
      │
      ▼
SQL Data Cleaning & Extraction
      │
      ▼
Python Data Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Random Forest Model
      │
      ▼
Model Evaluation
      │
      ▼
Customer Churn Prediction
      │
      ▼
Power BI Dashboard
```

---

# 🛠️ Tech Stack

### Programming
- Python
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- Random Forest Classifier

### Database
- SQL Server

### Visualization
- Power BI

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

# 📂 Repository Structure

```
├── Customer_Data.csv
├── Predictions.csv
├── main.ipynb
├── sql_queries.sql
├── Churn Analysis.pbix
├── preprocessing_artifacts.pkl
├── preprocessing_visualization.png
└── README.md
```

---

# 🤖 Machine Learning Pipeline

### Data Preprocessing

- Missing value handling
- Data cleaning
- Feature transformation
- Label Encoding
- One-Hot Encoding

---

### Feature Engineering

Features used include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Online Security
- Streaming Services

---

### Model Training

A **Random Forest Classifier** was trained to classify customers into:

- Churn
- No Churn

---

### Model Evaluation

Performance was evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC-AUC Score

**ROC-AUC Score:** **0.916**

---

# 📈 Power BI Dashboard

The dashboard provides interactive business insights through:

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
- Churn by Services

### Prediction Dashboard

- State-wise churn prediction
- Risk segmentation
- Customer profile analysis
- Customers at Risk table

---

# 📊 Business Insights

- Customers with **Month-to-Month** contracts show the highest churn.
- Customers using **Fiber Optic Internet** have a higher churn rate.
- Customers with shorter tenure are more likely to leave.
- Lack of Online Security and Tech Support is associated with increased churn.
- Certain states exhibit higher churn concentrations.

---

# 📈 Results

| Metric | Score |
|---------|-------|
| ROC-AUC | **0.916** |

---

# 💼 Business Impact

This project enables businesses to:

- Predict churn before customers leave
- Improve retention strategies
- Identify high-risk customers
- Reduce revenue loss
- Support data-driven decision making

---

# 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- SHAP Explainability
- Streamlit deployment
- REST API using Flask/FastAPI
- Automated retraining pipeline

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Akshadgajapure/churn-prediction-analytics.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

Open the Power BI dashboard using **Power BI Desktop**.

---

# 📷 Dashboard Preview

> Add screenshots of your Power BI dashboards here.

```markdown
![Dashboard](images/dashboard1.png)

![Prediction Dashboard](images/dashboard2.png)
```

---

# 🧠 Skills Demonstrated

- SQL
- Python
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Random Forest
- Power BI
- Business Intelligence
- Data Visualization

---

# 👨‍💻 Author

**Akshad Gajapure**

Chemical Engineering Undergraduate | NIT Raipur

- GitHub: https://github.com/Akshadgajapure

---

⭐ If you found this project useful, consider starring the repository.
