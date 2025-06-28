# 🔁 Internship Task 3 – Churn Modelling

## 🧠 Objective
This task focused on predicting customer churn in a bank. The objective was to classify whether a customer will exit (churn) based on their demographics, credit score, account balance, and other features using machine learning techniques.

## 📊 Dataset
- **File Name:** churn_modelling.csv
- **Target Variable:** Exited (0 = Stayed, 1 = Left)
- **Features:** Geography, Gender, Age, Balance, Tenure, Credit Score, etc.

## 🛠️ Steps Performed

### 🔹 Data Cleaning
- Removed irrelevant columns: RowNumber, CustomerID, and Surname
- Handled missing values using forward fill

### 🔹 Encoding
- Label Encoded `Gender` column
- One-Hot Encoded `Geography` column

### 🔹 Feature Scaling
- Standardized numeric features for better model performance

### 🔹 Model Building
- Split data into training and testing sets (80/20)
- Trained a **Random Forest Classifier**

### 🔹 Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

## 📈 Results
- Model successfully predicted customer churn
- Accuracy and classification results show strong predictive performance

## 📦 Libraries Used
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## 🗂️ Files
- `INTERNSHIP TASK3.ipynb` – Complete Jupyter Notebook with code and results
- `README.md` – Project summary

## ✅ Status
Completed and submitted as part of internship Task 3.
