# 📉 Customer Churn Prediction using Random Forest

## 📌 Overview

This project predicts whether a customer will churn (leave a service) or stay based on customer demographic and usage data. A Random Forest Classifier is implemented and optimized using advanced techniques such as hyperparameter tuning, cross-validation, Out-of-Bag (OOB) evaluation, and ROC-AUC analysis.

## 🧠 Model Used

* Random Forest Classifier (Ensemble Learning)

## ⚙️ Workflow

1. Data loading and preprocessing
2. Handling missing values
3. Encoding categorical variables
4. Exploratory data analysis
5. Train-test split
6. Baseline Random Forest model
7. Hyperparameter tuning (e.g., number of trees, max depth)
8. Cross-validation for model validation
9. Out-of-Bag (OOB) score evaluation
10. Final model evaluation

## 📊 Features Used

Typical features include:

* Customer tenure
* Monthly charges
* Total charges
* Contract type
* Payment method
* Internet service
* Customer demographics

## 🔧 Model Optimization & Validation

* Hyperparameter tuning to improve performance
* Cross-validation to ensure generalization
* OOB score used as an internal validation method for Random Forest

## 📊 Evaluation Metrics

* Accuracy Score
* Cross-validation score
* OOB Score

## 📈 Result

The optimized Random Forest model demonstrates strong performance in predicting customer churn. The OOB scoring provides an additional unbiased estimate of model performance.

## 🚀 How to Run

* Open the notebook in Google Colab
* Run all cells sequentially

## 📁 Files

* `customer-churn-prediction-random-forest.ipynb`

## 📚 Key Learnings

* Ensemble learning with Random Forest
* Importance of hyperparameter tuning
* Cross-validation vs OOB validation
* Building reliable and generalizable ML models
