📊 Customer Churn Prediction (Customer Analytics)
📌 Project Overview

Customer churn — when customers stop using a company’s services — is a critical challenge in industries like telecom, banking, and SaaS.

In this project, I built a machine learning model to predict churn using the Telco Customer Churn dataset.
The analysis identifies key drivers of churn and provides business recommendations to improve customer retention.

🎯 Objectives

Predict which customers are likely to churn.

Identify the most important churn factors.

Build actionable insights for retention strategies.

Showcase end-to-end data science workflow: EDA → Feature Engineering → ML Models → Insights.

🗂️ Dataset

Source: Telco Customer Churn Dataset on Kaggle

Rows: 7,043 customers

Target Variable: Churn (Yes/No)

Key Features

Demographics: gender, SeniorCitizen, Partner, Dependents

Services: PhoneService, InternetService, StreamingTV, TechSupport

Billing: Contract, PaymentMethod, MonthlyCharges, TotalCharges

Tenure: tenure (number of months with company)

🔧 Tools & Libraries

Python: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

EDA: Churn distribution, tenure groups, contract type

ML Models: Logistic Regression, Random Forest, XGBoost

Visualization: Feature importance plots, churn trends

📊 Workflow

Data Cleaning

Converted TotalCharges to numeric & filled missing values

Encoded categorical features

Created tenure groups

Exploratory Data Analysis (EDA)

Churn rate by contract type, monthly charges, tenure

Visualized churn drivers

Modeling

Baseline: Logistic Regression

Advanced: Random Forest, XGBoost

Metrics: Accuracy, Precision, Recall, F1, ROC-AUC

Insights & Recommendations

Month-to-month contracts → highest churn risk

New customers (<1 year) churn more

High monthly charges → higher churn probability

📈 Results

Best model: Random Forest / XGBoost (~82–85% ROC-AUC)

Top churn drivers:

Contract type

Tenure length

Monthly charges

Tech support availability

📊 Example Feature Importance Plot:


🧾 Business Recommendations

Convert month-to-month customers into yearly contracts with loyalty programs.

Offer discounts or bundles to customers with high monthly charges.

Enhance tech support and customer service.

Focus retention efforts on new customers (<1 year).

📂 Project Structure
📁 customer-churn-prediction
│── 📓 customer_churn.ipynb   # Jupyter Notebook
│── 📊 images/                # EDA & model visualizations
│── 📑 README.md              # Project documentation
│── 📄 churn_data.csv         # Dataset (optional, link instead if large)

🚀 How to Run
# Clone repo
git clone https://github.com/yourusername/customer-churn-prediction.git

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook customer_churn.ipynb

✅ Deliverables

📓 Full analysis in Jupyter Notebook

📊 Visuals & dashboards for churn insights

📑 GitHub portfolio project for recruiters/clients

✨ This project demonstrates end-to-end data science skills in real-world customer analytics.
