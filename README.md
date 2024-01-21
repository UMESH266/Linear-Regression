# Linear-Regression

Linear regression is a widely used statistical method in data science for modeling the relationship between a dependent variable and one or more independent variables also called explanatory variables. The fundamental idea is to find the best-fitting linear equation that represents the relationship between the variables.

## 1. Simple-Linear-Regression

### 1.1 Model Representation:
In simple linear regression, there is one independent variable (feature) and one dependent variable (target). The relationship is represented as:

y = mx + b

where:
- y is the dependent variable,
- x is the independent variable,
- m is the slope of the line, and
- b is the y-intercept.

### 1.2 Objective:
The goal of simple linear regression is to find the values of \(m\) and \(b\) that minimize the sum of squared differences between the observed and predicted values.

### 1.3 Cost Function:
The cost function (or loss function) typically used is the Mean Squared Error (MSE), given by:

MSE = Square off (Actual - Predicted)

### 1.4 Parameter Estimation:
The parameters m and b are usually estimated using methods like the least squares method, where the partial derivatives of the cost function with respect to m and b are set to zero, and the resulting system of equations is solved.

## 2. Multiple Linear Regression:

### 2.1 Model Representation:
In multiple linear regression, there are multiple independent variables. The relationship is represented as:

y = b0 + b1.x1 + b2.x2 + ... + bn.xn

where:
- y is the dependent variable,
- (x1, x2,..., xn) are the independent variables,
- b0 is the y-intercept, and
- (b1, b2,...., bn) are the coefficients.

### 2.2 Objective:
The objective is similar to simple linear regression: find the coefficients that minimize the sum of squared differences between the observed and predicted values.

### 2.3 Cost Function:
The cost function for multiple linear regression is an extension of the one used in simple linear regression.

## 3. Assumptions of Linear Regression:

1. Linearity: The relationship between variables is assumed to be linear.
2. Independence: Residuals (the differences between observed and predicted values) should be independent.
3. Homoscedasticity: Residuals should have constant variance across all levels of the independent variable(s).
4. Normality of Residuals: Residuals are assumed to be normally distributed.
5. No Multicollinearity: Independent variables should not be highly correlated.

## 4. Applications:

Linear regression is used in various fields, including finance, economics, biology, and social sciences, for tasks like predicting sales, stock prices, housing prices, and more.

## 5. Implementation:

The Python code file contains Simple Linear regression solutions for two simple datasets and has different models with polynomial, Standard scaled, Log scaled, and Square root scaled modeling solutions for the same problems.

Problem statements:
1) Delivery_time -> Predict delivery time using sorting time 
2) Salary_hike -> Build a prediction model for Salary_hike
3) Prepare a prediction model for profit of 50_startups data. Do transformations to get better predictions of profit and make a table containing R2 value for each prepared model.
4) Consider only the below columns and prepare a prediction model for predicting the Price of Corolla.
Corolla<-Corolla("Price", "Age_08_04", "KM", "HP", "cc", "Doors", "Gears", "Quarterly_Tax", "Weight")

NOTE: These models assume the underlying relationship is linear, and their performance can be affected if the assumptions are violated. Regularization techniques like Ridge and Lasso regression are also used to address issues like multicollinearity and overfitting.

Thank you . . .
