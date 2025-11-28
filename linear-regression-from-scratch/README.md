# Project No. 1 – Linear Regression from Scratch

**Author:** Idris Benseghir  
**Date:** November 2025  
**Dataset:** `study_hours.csv`  

---

This project presents a comprehensive analysis of **simple linear regression** using two approaches:  

- A fully **manual implementation** (from scratch) using only **NumPy** and **Pandas**  
- A **validation model** built with **scikit-learn’s** `LinearRegression`  

The aim is not only to fit a predictive model but also to **derive, compute, and interpret every mathematical component**, including:  

- Pearson Correlation Coefficient (**r**)  
- Closed-form slope (**b₁**) and intercept (**b₀**)  
- Prediction function  
- Manual performance metrics:  
  - Coefficient of Determination (**R²**)  
  - Standard Error of the Estimate (**SEE**)  
  - Mean Absolute Error (**MAE**)  
  - Root Mean Squared Error (**RMSE**)  

Finally, both approaches are compared using **numerical metrics, regression line plots**, and **residual analysis**, demonstrating an almost perfect match between the manual and library-based implementations.

---

## Part 1 — Data Pre-Processing  

This section prepares the dataset for regression:  

- Load the CSV file using **pandas**  
- Inspect the data (`head()`, `shape()`, `info()`)  
- Verify that there are no missing values or invalid entries  
- Visualize the relationship between variables using a scatter plot  
- Compute the **Pearson correlation coefficient** manually and with NumPy  

*Goal: ensure the data is clean and understand the underlying pattern before modeling*  

---

## Part 2 — Manual Linear Regression  

All steps in this part are performed **from scratch**, using pure mathematical formulas:  

- Split the dataset into **80% training** and **20% testing**  
- Compute **slope (b₁)** and **intercept (b₀)** manually  
- Define a **manual prediction function**  
- Calculate manual performance metrics:  
  - R² Score  
  - Standard Error of the Estimate (SEE)  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  

*Goal: gain a full understanding of how linear regression works internally*  

---

## Part 3 — Scikit-Learn Linear Regression  

Here, the dataset is modeled using scikit-learn:  
`from sklearn.linear_model import LinearRegression`  
- Fit the model  
- Extract model slope (`coef_`)  
- Extract intercept (`intercept_`)  
- Predict values (`predict()`)  
- Evaluate with sklearn’s own functions  
  
*Goal: get a trusted baseline to validate the manual math.*   

---
**Part 4 — Manual vs Sklearn Comparison**  
This final part shows a side-by-side comparison:  
- Manual slope vs sklearn slope  
- Manual intercept vs sklearn intercept  
- Manual predictions vs sklearn predictions  
- Metrics comparison (MAE, RMSE, R², etc.)
  
The results match **almost perfectly** (small floating-point differences only).   
*Goal: prove that the manual implementation is mathematically correct.*   
