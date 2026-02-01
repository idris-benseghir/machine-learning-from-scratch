# Project No. 2 – Logistic Regression from Scratch


**Author:** Abdallah Idris Benseghir
**Date:** December 2025
**Dataset:** `Titanic Dataset`

---

**Project Description**
This project presents a complete implementation of Logistic Regression from scratch using NumPy and Pandas, followed by a validation against scikit-learn’s Logistic Regression model.

Rather than relying on high-level machine learning abstractions, the model is built manually to demonstrate a strong understanding of classification theory, optimization, and evaluation metrics.

---

**Objectives**

- Implement Logistic Regression without using machine learning libraries
- Understand and code the sigmoid function and log-loss
- Train the model using batch gradient descent
- Evaluate performance using manually computed metrics
- Validate results using scikit-learn
---

**Methodology Overview**

The project follows a structured machine learning pipeline:
Data Preparation
- Loaded and explored the Titanic dataset
- Handled missing values (Age, Embarked)
- Removed high-missing columns (Cabin)
- Encoded categorical variables
- Standardized numerical features manually
- Split data into training and testing sets (80/20)
---

**Model Implementation (From Scratch)**

- Initialized weights and bias
- Computed linear combinations of features
- Applied sigmoid activation
- Optimized parameters using batch gradient descent
- Generated predictions using a decision threshold (0.5)

**Model Evaluation**

A confusion matrix is constructed manually, from which the following metrics are computed:
- Accuracy
- Precision
- Recall
- F1 Score
The same metrics are then computed using scikit-learn for comparison and validation.

**Technologies Used**

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn (used only for comparison)

**Results**

The manually implemented model achieves competitive performance compared to scikit-learn’s Logistic Regression.
Minor differences are expected due to sklearn’s default regularization and solver configuration.

**Academic Value**

This project emphasizes conceptual understanding over convenience.
By implementing Logistic Regression manually, it demonstrates:
- Strong mathematical foundations
- Ability to translate theory into code
- Readiness for advanced study in Machine Learning, AI, and Data Science
