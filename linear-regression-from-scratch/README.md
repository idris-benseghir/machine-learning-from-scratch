# Mini Project No. 1 – Linear Regression from Scratch

**Author:** Idris Benseghir   
**Date:** November 2025   
**Dataset:** `study_hours.csv`  
---
This project conducts a complete analytical study of simple linear regression using both:  
 - A fully manual implementation (from scratch) using only **NumPy, Pandas** 
 - A validation model built using **scikit-learn’s** LinearRegression  
The objective is not only to fit a predictive model, but to **derive, compute, and interpret every mathematical component**, including:  
- Pearson Correlation Coefficient (r)  
- Closed-form slope (b₁) and intercept (b₀)  
- Prediction function  
- Manual performance metrics:  
  - Coefficient of Determination (R²)  
  - Standard Error of the Estimate (SEE)  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)
  
Finally, both approaches are compared through **numerical metrics, regression line plots**, and **residual analysis**, confirming an almost perfect match between theoretical and library-based implementations.

**Part 1 — Data Pre-Processing**  
This section prepares the dataset for regression:  
- Load the CSV file using pandas.  
- Inspect the data (head, shape, info).  
- Confirm no missing values or invalid entries.  
- Visualize the relationship using a scatter plot.  
- Compute Pearson correlation manually and with NumPy.

*Goal: ensure the data is clean and understand the pattern before modeling*

**Part 2 — Manual Linear Regression**
Everything in this part is done **from scratch**, using pure math:  
- Data Splitting 80% for training 20% for testing.  
- Model Fitting - Culculating the slope 'b1' and y intercept 'b0'  
- Manual Prediction Function.  
- Manual Accuracy Metrics:  
  - R² Score  
  - Standard Error of the Estimate (SEE)  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
    
*Goal: fully understand how linear regression works internally*  
