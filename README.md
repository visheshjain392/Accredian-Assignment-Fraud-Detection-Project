# Accredian-Assignment-Fraud-Detection-Project
Financial Fraud Detection using Machine Learning on 6.3M transactions with data analysis, feature engineering, and business-driven fraud prevention insights.

## Dataset
Due to GitHub file size limitations, the dataset is not included in this repository.

You can download it here:
[Download Dataset](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0)

Financial Fraud Detection Using Machine Learning
📌 Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning techniques. The goal is to analyze transaction behavior and build a predictive model that helps financial institutions identify fraud proactively.

📊 Dataset Information
Total Records: 6,362,620 transactions
Time Simulation: 30 days (744 hours)
Transaction Types: CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER
Target Variable: isFraud

🎯 Business Objective
To build a fraud detection system that:
Identifies suspicious transactions
Reduces financial loss
Supports real-time decision-making

🧹 Data Preprocessing
Handled missing values
Removed unnecessary ID columns
Performed outlier analysis
Checked multicollinearity
Feature engineering using balance differences

📈 Exploratory Data Analysis
Key findings:
Fraud mainly occurs in TRANSFER and CASH_OUT transactions.
Fraud transactions often involve large amounts.
Fraudsters attempt to empty customer accounts quickly.

🤖 Model Development
Models Used:
Logistic Regression (baseline)
Random Forest Classifier
Evaluation Metrics:
Precision
Recall
F1 Score
ROC-AUC

🔍 Key Fraud Indicators
High transaction amount
Sudden balance reduction
Transfer transactions
Cash-out behavior

🛡️ Business Recommendations
Real-time fraud monitoring system
Multi-factor authentication for risky transactions
Transaction limit alerts
Behavior-based anomaly detection

📊 Success Measurement
Reduction in fraud loss
Improved detection rate
Lower false positives
Faster fraud detection time

🛠️ Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

👤 Author
Vishesh Jain
MCA Student | Data Analytics & Data Science Enthusiast
