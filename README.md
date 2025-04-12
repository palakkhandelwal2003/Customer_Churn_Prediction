# 📊 Customer Churn Prediction

This project uses machine learning models to predict whether a customer will churn (leave the service) based on Telco customer data. It includes data preprocessing, feature encoding, balancing using SMOTE, model training with Random Forest and XGBoost, and deployment using Pickle.

---

## 📁 Dataset

The dataset used is the **Telco Customer Churn dataset** which includes customer demographics, account information, and service usage.

---

## 🚀 Features

- Data cleaning and preprocessing  
- Categorical feature encoding using LabelEncoder  
- Handling class imbalance using SMOTE  
- Model training with:
  - Decision Tree
  - Random Forest
  - XGBoost
- Model evaluation using accuracy, confusion matrix, classification report  
- Model saving and loading with Pickle  
- Making predictions on new data  

---

## 🧪 Installation & Requirements

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost

