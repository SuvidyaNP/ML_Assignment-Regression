# ML_Assignment-Regression
**Regression Algorithm Comparison**

**Overview:**
This project implements and compares the performance of various regression algorithms on the California Housing dataset (fetch_california_housing). The objective is to evaluate and identify the best-performing algorithm using common evaluation metrics.

**Algorithms Implemented**
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)

**Dataset**
Name: fetch_california_housing (from sklearn.datasets)

**Steps Implemented**
**1. Data Preprocessing:**

- Loaded the dataset using fetch_california_housing.
- Standardized the features using StandardScaler to ensure all variables have equal importance.

**2. Model Training:**

a-Split the data into training and testing sets.
b-Trained the following models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- SVR

**3. Model Evaluation:**

Evaluated each model using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared Score (R²)

**4. Comparison**

-Identified the best-performing algorithm (Random Forest Regressor) and worst-performing algorithm (Linear Regression).
-Justifications were provided for the selection of these algorithms.


**Conclusion**
This project demonstrates how to train and evaluate multiple regression models while identifying the best-suited algorithm for a specific dataset. The Random Forest Regressor outperforms others due to its ability to handle nonlinear relationships and robustness against overfitting.
