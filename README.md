Nigerian Telecom Customer Churn Prediction
📊 Project Overview
This project builds and compares machine learning models to predict customer churn in the Nigerian telecommunications industry. With over 200 million active subscribers across four major providers (MTN Nigeria, Airtel Nigeria, Glo, and 9mobile), retaining existing customers is 5x more cost-effective than acquiring new ones.

🎯 Business Problem
Customer churn costs telecom companies millions in lost revenue. By predicting which customers are likely to churn, providers can proactively offer retention incentives such as:

Personalised data bonuses

Loyalty rewards programs

Targeted customer care calls

Tailored promotional offers

📁 Dataset
The project uses two datasets:

1. telecom_demographics.csv (6,500 customers)
customer_id: Unique identifier

telecom_partner: Provider (MTN, Airtel, Glo, 9mobile)

gender: Customer gender

age: Customer age

state: Nigerian state

city: City location

pincode: Area postal code

registration_event: Registration date

num_dependents: Number of dependents

estimated_salary: Estimated monthly income (NGN)

2. telecom_usage.csv (6,500 customers)
customer_id: Unique identifier

calls_made: Number of calls in last 30 days

sms_sent: Number of SMS messages in last 30 days

data_used: Mobile data used (MB)

churn: Target variable (1 = churned, 0 = active)

🔧 Project Tasks
Task 1: Data Loading & Exploration
Load and merge both datasets

Calculate churn rate (20.05%)

Identify categorical variables for encoding

Task 2: Feature Preprocessing
One-hot encode categorical variables

Drop non-predictive columns

Scale numeric features using StandardScaler

Task 3: Model Training
Two models were trained and compared:

Logistic Regression with class_weight='balanced'

Random Forest with class_weight='balanced'

Task 4: Model Evaluation
Accuracy scores

Classification reports (precision, recall, F1-score)

Model comparison and selection

🛠️ Technologies Used
Python 3.8+

pandas - Data manipulation

numpy - Numerical operations

scikit-learn - Machine learning models and preprocessing

imbalanced-learn - SMOTE for class balancing

Jupyter Notebook - Development environment

🚀 How to Run
Clone this repository

Install required libraries:

bash
pip install pandas numpy scikit-learn imbalanced-learn
Place CSV files in the same directory as the notebook

Run the Jupyter Notebook:

bash
jupyter notebook "TikedzaniGeraldine_Vele_Capstone_2026.ipynb"
📂 Repository Structure
text
├── Tikedzani_Vele_Capstone_2026.ipynb  # Main notebook
├── telecom_demographics_nigeria.csv              # Demographics dataset
├── telecom_usage.csv                             # Usage dataset
└── README.md                                     # This file


👩‍💻 Author
Tikedzani Geraldine Vele
AIC Africa Data Science Student

📅 Project Details
Course: AIC Africa Data Science Capstone Project

Year: 2026

Institution: AIC Africa
