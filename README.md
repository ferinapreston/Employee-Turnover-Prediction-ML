# Employee-Turnover-Prediction-ML
# 🧠 Employee Turnover Analytics – Machine Learning Project

This project explores and predicts employee turnover for **Portobello Tech**, an app innovation company, using a machine learning pipeline. The HR Department seeks to analyze past employee data to identify key drivers of resignation and develop actionable retention strategies.

---

## 🧾 Project Objective

Portobello Tech periodically evaluates its employees based on performance metrics such as:

- Number of projects
- Average monthly working hours
- Years at the company
- Promotions in the last 5 years
- Salary level
- Satisfaction scores
- Work evaluation ratings

The HR team wants to leverage this data to:

1. **Predict if an employee is likely to leave**
2. **Understand the reasons behind turnover**
3. **Cluster employees based on work evaluation & satisfaction**
4. **Address class imbalance using SMOTE**
5. **Train and evaluate ML models using cross-validation**
6. **Suggest retention strategies**

---

## 📂 Dataset Overview

- **Source:** Internal HR dataset from Portobello Tech
- **Target Variable:** `left` (0 = stayed, 1 = left)
- **Features Include:**
  - Satisfaction level
  - Last evaluation score
  - Number of projects
  - Average monthly hours
  - Time spent at the company
  - Work accident
  - Promotion in the last 5 years
  - Department
  - Salary

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – Data preprocessing
- **Matplotlib & Seaborn** – EDA and Visualization
- **Scikit-learn** – ML modeling & evaluation
- **Imbalanced-learn** – SMOTE for class imbalance
- **KMeans** – Clustering
- **K-Fold Cross Validation**

---

## 📊 Workflow & Key Steps

### ✅ 1. Data Quality Check
- Verified missing/null values
- Checked for data inconsistencies or skew

### 📈 2. Exploratory Data Analysis (EDA)
- Analyzed features that most influence attrition
- Correlation heatmaps, boxplots, and histograms were used to explore trends

### 🔍 3. Clustering (KMeans)
- Clustered employees who left using `satisfaction_level` and `last_evaluation`
- Identified potential behavioral patterns in exits

### ⚖️ 4. Class Imbalance Handling
- Used **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset

### 🤖 5. Model Training & Cross-Validation
- Trained ML models using **K-Fold Cross-Validation**
- Evaluated performance with metrics like **accuracy, precision, recall, F1-score**

### 🏆 6. Model Selection & Justification
- Compared Logistic Regression, Decision Tree, Random Forest, etc.
- Selected the best model based on balanced F1-score and overall generalization

### 🛡️ 7. Employee Retention Strategies
- Based on model insights and clusters, strategies were proposed for:
  - Overworked or under-promoted employees
  - Employees with high evaluations but low satisfaction
  - Low-salary groups with high attrition risk

---

## 📈 Sample Visuals

- Satisfaction vs. Evaluation Cluster Plot
- Feature Importance Chart
- Class Distribution Before/After SMOTE
- ROC Curves for Model Comparison

---

## ✅ Outcome

This project empowers the HR Department at Portobello Tech to:
- Predict attrition proactively
- Design targeted interventions
- Optimize workforce planning
- Improve employee satisfaction and retention

---
