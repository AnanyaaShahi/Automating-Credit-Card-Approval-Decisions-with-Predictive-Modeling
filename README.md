# Automating-Credit-Card-Approval-Decisions-with-Predictive-Modeling

**Project Overview**
This project aims to automate the process of credit card approval by leveraging machine learning techniques. Commercial banks receive thousands of applications, and manually reviewing them is time-consuming and prone to errors. By using machine learning, we can efficiently classify applicants as eligible or ineligible for credit card approval based on their financial and demographic information.

**Introduction**
Financial institutions rely on credit scoring models to evaluate loan applicants. The goal of this project is to:

* Develop a machine learning model to predict credit card approvals.
* Address challenges such as class imbalance and feature selection.
* Compare different classification models to determine the best-performing approach.
  
**Dataset Description**

* The dataset is sourced from Kaggle, containing 25,128 rows and 21 columns.
* Features include demographic information, financial history, employment details, and credit utilization.
* One of the major challenges with the dataset is class imbalance, which is mitigated using SMOTE (Synthetic Minority Over-sampling Technique).
  
**Methodology**
The project follows these key steps:

* Exploratory Data Analysis (EDA) – Understanding data distribution, missing values, and feature relationships.
* Data Cleaning – Handling missing values, outliers, and encoding categorical features.
* Feature Engineering – Creating new features and transforming existing ones.
* Handling Class Imbalance – Using SMOTE to balance 'good' and 'bad' credit applicants.
* Model Training and Evaluation – Applying Logistic Regression and Random Forest models.
  
**Techniques and Models Used**

* Logistic Regression
* GridSearchCV for hyperparameter tuning.
* Evaluated using precision, recall, F1-score, accuracy, and ROC-AUC.
* Random Forest Classifier
* Feature importance analysis.
* Hyperparameter tuning with GridSearchCV.
  
**Results**

**Logistic Regression**

*Achieved perfect classification with 100% accuracy, precision, recall, and F1-score.
*Most important feature: Total_Good_Debt.

**Random Forest**

* Also achieved 100% accuracy.
* Most significant features: Total_Good_Debt, Total_Bad_Debt, and Owned_Realty_1.
  
**Learnings**

* Addressing class imbalance was critical for model performance.
* Feature selection played a significant role in improving accuracy.
* The dataset might have contributed to overfitting, as the models achieved perfect scores.
