# Customer Satisfaction (CSAT) Prediction using Machine Learning

## Project Overview
Customer satisfaction is a key indicator of service quality in customer support systems. This project analyzes customer support interaction data and builds machine learning models to predict Customer Satisfaction Score (CSAT). By identifying the factors influencing satisfaction, organizations can improve customer support services and enhance overall customer experience.

This project applies data preprocessing, exploratory data analysis, feature engineering, and machine learning techniques to predict CSAT scores based on features such as issue category, response time, agent information, and customer interaction details.

---

## Problem Statement
Customer support teams handle large volumes of customer interaction data. Analyzing this data manually to understand the factors affecting customer satisfaction is difficult and time-consuming.

The goal of this project is to build a machine learning model that predicts customer satisfaction scores (CSAT) using historical customer support interaction data. The insights from the model can help organizations identify issues affecting customer satisfaction and improve service quality.

---

## Dataset Description
The dataset contains information related to customer support interactions.

### Key Features
- Unique ID
- Channel Name
- Category
- Sub-category
- Customer Remarks
- Order ID
- Issue Reported Time
- Response Time
- Customer City
- Product Category
- Agent Name
- Agent Shift
- Tenure Bucket
- CSAT Score (Target Variable)

The dataset contains **85,000+ records** with multiple categorical and numerical features.

---

## Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Dropping irrelevant columns
- Converting date columns to datetime format
- Encoding categorical variables

### 2. Exploratory Data Analysis (EDA)
- CSAT score distribution
- Issue category analysis
- Agent performance analysis
- Response time analysis
- Correlation analysis

### 3. Feature Engineering
- Extracting time features
- Creating new variables
- Encoding categorical features

### 4. Machine Learning Models
The following models were implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### 5. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Hyperparameter tuning was performed using **GridSearchCV**.

### 6. Model Explainability
Feature importance was analyzed using Random Forest to understand the most important factors influencing customer satisfaction.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## Key Insights
- Response time strongly impacts customer satisfaction.
- Certain issue categories lead to lower CSAT scores.
- Customer interaction patterns influence satisfaction levels.
- The dataset shows a higher frequency of high CSAT ratings.

---

## Conclusion
This project demonstrates how machine learning techniques can be used to analyze customer support data and predict customer satisfaction levels. By identifying the factors that influence CSAT scores, organizations can improve their customer service strategies and enhance customer experience.

---
