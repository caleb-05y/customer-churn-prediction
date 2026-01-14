# Telco Customer Churn Prediction

**End-to-end machine learning project analyzing customer churn using Logistic Regression and Random Forest with business-driven model evaluation.**

---

## 🧩 Project Overview

Customer churn prediction is a critical business problem in the telecom industry.  
This project builds and compares supervised machine learning models to identify customers at risk of churning.

The workflow follows a **real-world ML pipeline**, from raw data preprocessing to model evaluation and business decision-making.

---

## 🎯 Objective

- Predict whether a customer will churn
- Compare models using **business-relevant metrics**
- Select the most appropriate model for customer retention strategies

---

## 📂 Dataset

- Telco Customer Churn dataset
- 7,000+ customer records
- Mix of numerical and categorical features
- Binary churn target variable

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas & NumPy** – Data cleaning and preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **scikit-learn** – Modeling and evaluation
  - Logistic Regression
  - Random Forest Classifier
  - StandardScaler
  - Classification metrics

---

## 📊 Workflow

### 1. Data Cleaning & Preprocessing
- Converted `TotalCharges` to numeric
- Handled missing values
- Dropped irrelevant identifiers
- Encoded categorical variables using dummy encoding
- Scaled numerical features for Logistic Regression

### 2. Exploratory Data Analysis
- Correlation heatmap to understand feature relationships
- Initial insights into churn drivers

### 3. Model Development
- **Logistic Regression** with scaled features
- **Random Forest** with 300 estimators and out-of-bag validation

### 4. Model Evaluation
Models evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Out-of-Bag (OOB) error for Random Forest

---

## 📈 Model Performance Summary

### Logistic Regression
- Accuracy: **81.3%**
- Precision: **68.5%**
- Recall: **57.7%**
- F1 Score: **62.6%**

### Random Forest
- Accuracy: **79.6%**
- Precision: **67.9%**
- Recall: **47.6%**
- F1 Score: **55.9%**
- OOB Error: **~21%**

---

## 🧠 Business-Focused Model Selection

The primary business goal is **customer retention**, making **Recall** the most important metric.

- Logistic Regression identifies **more true churners**
- Random Forest has slightly higher accuracy but misses more churn cases

### ✅ Final Decision:
**Logistic Regression** is the preferred model due to:
- Higher recall
- Better alignment with business objectives
- Greater interpretability for stakeholders

---

## 🚀 Skills Demonstrated

- End-to-end machine learning workflow
- Feature engineering and preprocessing
- Supervised model comparison
- Business-driven metric selection
- Model interpretability and evaluation
- Practical use of scikit-learn

---

## 📬 Contact

- GitHub: [your GitHub handle]
- LinkedIn: [your LinkedIn profile]

This project is part of my professional data science portfolio and demonstrates applied machine learning for real-world business problems.
