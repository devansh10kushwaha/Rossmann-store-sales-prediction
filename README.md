# Rossmann-store-sales-prediction
This project focuses on predicting daily sales for Rossmann stores using Machine Learning techniques. The goal is to analyze historical sales data and forecast future store sales accurately based on various business and environmental factors.

Project Overview

Retail stores need accurate sales predictions to understand expected revenue and make better decisions regarding promotions, inventory, staffing, and store operations.

This project develops a machine learning model that predicts daily sales based on information such as:

Store ID,
Day of the week,
Promotions,
State holidays,
School holidays,
Store type,
Assortment type,
Competition distance,
Competition opening duration,
Date-related features,
Promo2 information

Machine Learning Workflow :

Raw Dataset
     ↓
Data Cleaning
     ↓
Missing Value Handling
     ↓
Feature Engineering
     ↓
Categorical Encoding
     ↓
Numerical Scaling
     ↓
Train / Validation Split
     ↓
XGBoost Regression
     ↓
Model Evaluation
     ↓
Model Serialization
     ↓
Streamlit Dashboard
     ↓
Sales Prediction

XGBRegressor( n_jobs=-1, random_state=42, n_estimators=1000, learning_rate=0.2, max_depth=10, subsample=0.9, colsample_bytree=0.7 )

Technologies Used:

Python,
Pandas,
NumPy,
Scikit-learn,
XGBoost,
Joblib,
Streamlit,
Jupyter Notebook
