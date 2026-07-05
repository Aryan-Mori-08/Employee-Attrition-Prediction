# Employee Attrition Prediction Using Machine Learning

## Overview

This project focuses on predicting whether an employee is likely to **stay with the organization** or **leave (attrition)** using various Machine Learning classification algorithms.

The dataset used in this project was already preprocessed and encoded, allowing the primary focus to be on model development, training, evaluation, and comparison. Multiple machine learning models were implemented to identify the algorithm that provides the highest prediction accuracy.

---

## Dataset

- **Dataset:** Employee Attrition Dataset
- **Problem Type:** Binary Classification
- **Target Variable:** Attrition
  - **0:** Employee Stays
  - **1:** Employee Leaves

> **Note:** The dataset was already cleaned, preprocessed, and encoded before model development. Therefore, no additional data preprocessing or exploratory data analysis (EDA) was performed in this project.

---

## Project Workflow

### 1. Data Loading
- Imported the preprocessed dataset.
- Split the dataset into training and testing sets.

### 2. Model Development
Implemented and trained multiple machine learning classification algorithms.

### 3. Model Evaluation
- Evaluated each model using testing accuracy.
- Compared the performance of all models.
- Applied hyperparameter tuning to improve K-Nearest Neighbors (KNN) performance.

---

## Machine Learning Models

The following machine learning algorithms were implemented and evaluated.

| Model | Testing Accuracy |
|--------|-----------------:|
| Logistic Regression | **85.92%** |
| Naive Bayes | **83.33%** |
| K-Nearest Neighbors (Default) | **80.37%** |
| KNN (After GridSearchCV Hyperparameter Tuning) | **84.37%** |
| Decision Tree | **85.18%** |
| Support Vector Machine (SVM) | **89.25%** |
| Random Forest | **84.07%** |
| XGBoost | **90.00%** |
| Gradient Boosting | **92.00%** |

---

## Model Comparison

- Logistic Regression achieved a strong baseline accuracy of **85.92%**.
- Naive Bayes provided competitive performance with **83.33%** accuracy.
- Hyperparameter tuning using **GridSearchCV** improved the KNN model from **80.37%** to **84.37%**.
- Decision Tree produced an accuracy of **85.18%**.
- Support Vector Machine (SVM) significantly improved performance with **89.25%** accuracy.
- XGBoost achieved an excellent testing accuracy of **90.00%**.
- **Gradient Boosting** was the best-performing model with a testing accuracy of **92.00%**.

---

## Best Performing Model

| Model | Testing Accuracy |
|--------|-----------------:|
| **Gradient Boosting** | **92.00%** |

Gradient Boosting outperformed all other implemented algorithms, making it the most accurate model for predicting employee attrition on this dataset.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost


---

## Project Outcomes

- Built and evaluated nine machine learning classification models.
- Compared model performance using testing accuracy.
- Improved KNN performance through hyperparameter tuning with GridSearchCV.
- Identified Gradient Boosting as the most effective model for employee attrition prediction.


---

## Conclusion

This project demonstrates the application of multiple machine learning algorithms for employee attrition prediction using an already preprocessed and encoded dataset.

A total of **nine classification models** were trained and evaluated. Among them, **Gradient Boosting** achieved the highest testing accuracy of **92.00%**, followed by **XGBoost (90.00%)** and **Support Vector Machine (89.25%)**. The project highlights the importance of comparing multiple algorithms and applying hyperparameter tuning to identify the most suitable model for employee attrition prediction.
