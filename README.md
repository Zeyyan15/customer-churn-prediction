# 📊 Customer Churn Prediction

This project focuses on predicting **customer churn** for a business, i.e., identifying customers who are likely to stop using the service. Retaining customers is far more cost-effective than acquiring new ones, and predictive modeling can help businesses take proactive steps to reduce churn.  

---

## 📌 Project Overview
- **Goal**: Build a classification model that predicts whether a customer will churn.  
- **Dataset**: Telco-style `customer.csv` dataset (contains customer demographics, services subscribed, and churn status).  
- **Approach**: Data preprocessing → Model training → Evaluation using Accuracy & Confusion Matrix.  

---

## 🚀 Steps Implemented

### 1. Data Preprocessing
- Handled missing values.  
- Converted categorical variables into numerical values using **Label Encoding / One-Hot Encoding**.  
- Normalized numerical features for better model performance.  

### 2. Train-Test Split
- Split dataset into **80% training** and **20% testing** sets.  

### 3. Model Training
- Used **Logistic Regression** as the baseline classification model.  

### 4. Model Evaluation
- Measured model performance with:
  - **Accuracy Score** 📈  
  - **Confusion Matrix** 🔢  

---

## 📊 Results
- **Accuracy Achieved**: ~79.5% .  
- **Confusion Matrix Interpretation**:
  - **True Positives (TP)**: Correctly predicted churn customers.  
  - **True Negatives (TN)**: Correctly predicted non-churn customers.  
  - **False Positives (FP)**: Predicted churn but customer stayed.  
  - **False Negatives (FN)**: Missed churn customers.  

This matrix provides insights into whether the model is better at catching churners or avoiding false alarms.  

---

## 🛠️ Tech Stack
- **Python 3.x**  
- **Pandas, NumPy** – Data cleaning & preprocessing  
- **Scikit-learn** – Model training & evaluation  
- **Matplotlib, Seaborn** – Visualization  

---

