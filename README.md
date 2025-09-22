# Customer Churn Analysis – EDA & Modeling

## 📌 Overview
This project explores customer churn through **Exploratory Data Analysis (EDA)** and **predictive modeling**.  
Customer churn (or attrition) occurs when customers stop using a company’s product or service, directly affecting revenue and long-term profitability. Identifying patterns behind churn is crucial for improving customer retention and business growth.  

## 📂 Dataset
The dataset used: [Credit Card Customer Churn Prediction (Kaggle)](https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction/data).  

Key features include:  

- **Demographics:** Geography, Gender, Age, Surname  
- **Account details:** CreditScore, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary  
- **Target variable:** `Exited` (1 = Churned, 0 = Retained)  

## ⚙️ Requirements
Install the following Python libraries before running the notebook:  

## 🔑 Project Highlights

📊 Exploratory Data Analysis (EDA):

Identified patterns and trends in customer demographics and account activity.

Visualized correlations between features (e.g., age, balance, activity status) and churn behavior.

## ⚖️ Handling Class Imbalance:

Used SMOTE (Synthetic Minority Over-sampling Technique) and class weighting to address imbalance in the churn dataset.

## 🤖 Machine Learning Models:

Implemented and compared multiple classifiers:

Logistic Regression

Random Forest

K-Nearest Neighbors

Support Vector Machine

XGBoost

Gradient Boosting

## 🧮 Model Evaluation:

Compared models using Accuracy, Recall, F1 Score, and ROC AUC to assess predictive performance.

## 🏆 Best Performing Models:

Gradient Boosting achieved the highest F1 and ROC AUC, making it the most reliable for churn prediction.

XGBoost followed closely with competitive results.
