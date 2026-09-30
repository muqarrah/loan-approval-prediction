# 🏦 Loan Approval Prediction System

An end-to-end Machine Learning web application that predicts loan application approval using Logistic Regression based on applicant demographics, financial history, and loan requirements.

---

## 📌 Problem Statement
Financial institutions manually evaluate loan applications, which can be time-consuming and subjective. This project automates the credit risk assessment process by predicting whether a loan application should be **Approved** or **Rejected** based on historical applicant data.

---

## 📊 Dataset & Preprocessing
* **Source:** Analytics Vidhya Loan Prediction Dataset (614 rows, 13 columns).
* **Missing Values Imputation:**
  * Categorical features (`Gender`, `Married`, `Dependents`, `Self_Employed`, `Credit_History`) filled using **Mode**.
  * Numerical features (`LoanAmount`) filled using **Median**.
* **Feature Encoding:** Applied `LabelEncoder` on categorical fields (`Gender`, `Education`, `Property_Area`, `Loan_Status`).

---

## ⚙️ Model & Performance
* **Algorithm:** Logistic Regression
* **Train/Test Split:** 80% Train / 20% Test

### Performance Metrics
| Metric | Value |
| :--- | :--- |
| **Accuracy** | ~78.86% |
| **Precision** | ~75.90% |
| **Recall** | ~98.00% |
| **F1-Score** | ~85.50% |
| **ROC-AUC** | ~0.78 |

---
