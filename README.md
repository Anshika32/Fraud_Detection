# Fraud Detection Machine Learning Model

🔍 This repository contains code for developing and evaluating machine learning models for fraud detection in financial transactions.

## Overview

The goal of this project is to predict fraudulent transactions using various machine learning algorithms and provide insights for developing actionable strategies.

## Dataset

The dataset used (`Fraud.csv`) contains financial transaction data with attributes like amount, balance changes, transaction type, and whether the transaction is fraudulent or not.

## Machine Learning Pipeline

### Data Preprocessing

- **Data Cleaning**: Handle missing values and remove outliers using statistical methods.
- **Feature Engineering**: Encode categorical variables and normalize numerical features.
- **Class Imbalance**: Address class imbalance using the NearMiss technique for undersampling.

### Model Building

Several machine learning models are evaluated:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Gaussian Naive Bayes
- K Nearest Neighbors (KNN) Classifier
- Support Vector Classifier (SVC)
- XGBoost Classifier

### Model Evaluation

Evaluate each model using metrics such as:

- ROC AUC Score
- F1 Score
- Confusion Matrix
- Accuracy Score

### Hyperparameter Tuning

Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV for selected models to optimize performance.

## Results

Compare the performance of different models and discuss insights gained from each model's predictions.
