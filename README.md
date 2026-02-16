# -Customer-Churn-Prediction-Bank-Customers-
Project Overview

This project aims to predict whether a bank customer is likely to leave the bank (churn) using machine learning classification techniques. By analyzing customer data, the model helps understand key factors influencing churn and supports better customer retention strategies.

 Objective
To build a supervised machine learning model that predicts customer churn and identifies important features affecting customer decisions.

📂 Dataset

Churn Modelling Dataset

The dataset includes the following types of features:
Customer Demographics: Age, Gender, Geography
Account Information: Credit Score, Balance, Number of Products, Estimated Salary

Target Variable:

Exited = 1 → Customer left the bank
Exited = 0 → Customer stayed with the bank

⚙️ Methodology
1. Data Cleaning & Preparation

Removed irrelevant columns (RowNumber, CustomerId, Surname)
Checked and handled missing values
Prepared target variable for modeling

2. Categorical Data Encoding
Applied Label Encoding for binary categorical features (Gender)
Applied One-Hot Encoding for multi-category features (Geography)

3. Model Training

Split the dataset into training and testing sets
Trained a classification model such as:
Logistic Regression
Decision Tree
Random Forest

4. Feature Importance Analysis

Analyzed feature importance to identify which variables most affect churn
Key influencing features include Age, Balance, Geography, and Number of Products

 Skills & Techniques Used:
Data Cleaning and Preprocessing
Categorical Data Encoding (Label Encoding, One-Hot Encoding)
Supervised Machine Learning Classification
Feature Importance Interpretation
Model Evaluation (Accuracy, Confusion Matrix)

 Model Evaluation:

The model performance is evaluated using:
Accuracy Score
Confusion Matrix
Classification Report

✅ Results

The trained model can successfully predict whether a customer will churn. Feature importance analysis provides insights into customer behavior and supports business decision-making.

🛠 Tools & Libraries

Python
Pandas
NumPy
Matplotlib / Seaborn

Scikit-learn

📁 Project Structure
Customer-Churn-Prediction/
│
├── churn_dataset.csv
├── churn_prediction.ipynb
├── README.md  
