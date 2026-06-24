# Employee Attrition Prediction using Machine Learning

## Project Overview

Employee attrition is a major challenge for organizations because replacing employees requires significant time, cost, and resources. This project aims to predict whether an employee is likely to leave the company based on various workplace and personal factors such as job satisfaction, monthly income, work-life balance, overtime, and years at the company.

Using the IBM HR Analytics Employee Attrition dataset, multiple machine learning models were developed and compared to identify the most effective approach for predicting employee turnover and generating actionable HR insights.

---

## Objectives

* Analyze employee attrition patterns.
* Identify factors influencing employee turnover.
* Build predictive machine learning models.
* Compare model performance using standard evaluation metrics.
* Provide business recommendations for HR teams.

---

## Dataset

Dataset: IBM HR Analytics Employee Attrition Dataset

* Total Records: 1,470 employees
* Target Variable: Attrition (Yes/No)

Features include:

* Age
* Department
* Job Role
* Monthly Income
* Job Satisfaction
* Work-Life Balance
* Overtime
* Years at Company
* Performance Rating
* Education Level
* And several other HR-related attributes

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Exploration

* Loaded and explored HR data
* Examined employee attrition distribution
* Identified numerical and categorical features

### 2. Data Preprocessing

* Removed irrelevant columns
* Encoded categorical variables using One-Hot Encoding
* Scaled numerical features using StandardScaler
* Prepared data for machine learning models

### 3. Exploratory Data Analysis (EDA)

Analyzed:

* Attrition by Department
* Attrition by Job Role
* Attrition vs Monthly Income
* Attrition vs Work-Life Balance
* Attrition vs Years at Company

### 4. Model Development

The following classification models were trained and compared:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

### 5. Model Evaluation

Models were evaluated using:

* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

### 6. Feature Importance Analysis

Identified the most influential factors contributing to employee attrition.

---

## Key Insights

* Employees with lower job satisfaction were more likely to leave.
* Overtime showed a strong relationship with attrition.
* Employees in certain departments and job roles experienced higher turnover.
* Lower income groups generally had higher attrition rates.
* Attrition was highest during the early years of employment.

---

## Business Recommendations

* Focus retention programs on employees during their first few years.
* Improve work-life balance initiatives.
* Monitor employee satisfaction regularly.
* Reduce excessive overtime where possible.
* Provide clearer career growth opportunities for high-risk employee groups.

---

## Repository Structure

```text
EmployeeAttrition_HarshitBind/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── summary.pdf
│
└── charts/
    ├── attrition_department_jobrole.png
    ├── income_vs_attrition.png
    ├── confusion_matrix.png
    ├── feature_importance.png
    └── roc_curve.png
```

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* SMOTE for class imbalance handling
* Deployment using Streamlit or Flask
* Real-time HR dashboard development

---

## Author

Harshit Bind

B.Tech Computer Science & Engineering

Data Analytics & Machine Learning Enthusiast
