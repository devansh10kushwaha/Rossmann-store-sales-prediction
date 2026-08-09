# Rossmann-store-sales-prediction
This project focuses on predicting daily sales for Rossmann stores using Machine Learning techniques. The goal is to analyze historical sales data and forecast future store sales accurately based on various business and environmental factors.

Project Overview

Retail stores need accurate sales predictions to understand expected revenue and make better decisions regarding promotions, inventory, staffing, and store operations.

This project develops a machine learning model that predicts daily sales based on information such as:

Store ID
Day of the week
Promotions
State holidays
School holidays
Store type
Assortment type
Competition distance
Competition opening duration
Date-related features
Promo2 information

The trained model is integrated into a Streamlit web dashboard, allowing users to enter store information and instantly obtain a predicted sales value.

Objectives

Analyze the Rossmann store sales dataset.
Perform data cleaning and preprocessing.
Handle missing values.
Engineer useful date and promotion features.
Encode categorical variables.
Scale numerical features.
Train an XGBoost regression model.
Evaluate the model using regression metrics.
Save the trained model and preprocessing objects.
Build an interactive Streamlit dashboard for sales prediction.

Machine Learning Workflow

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
