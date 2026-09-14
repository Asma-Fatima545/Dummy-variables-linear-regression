# Dummy Variables & Multiple Linear Regression

## Overview

This project demonstrates how a categorical variable can be converted into a numerical dummy variable and incorporated into a multiple linear regression model using Python.

The analysis uses student performance data to examine the relationship between **GPA, SAT scores, and attendance**.

## Dataset

The dataset contains **84 observations** with the following variables:

* **SAT** – SAT score
* **GPA** – Grade Point Average
* **Attendance** – Whether the student attended classes (`Yes` / `No`)

The categorical `Attendance` variable was converted into a binary dummy variable:

* `Yes` → `1`
* `No` → `0`

## Analysis Performed

* Imported and explored the dataset using **Pandas**
* Converted a categorical variable into a numerical dummy variable
* Generated descriptive statistics
* Defined the dependent and independent variables
* Built a **Multiple Linear Regression** model using `statsmodels`
* Examined regression coefficients and statistical significance
* Evaluated model performance using **R-squared**
* Created visualisations to compare the relationship between SAT scores, GPA, and attendance
* Used the regression model for prediction

## Regression Model

The model uses:

**Dependent variable:**

* GPA

**Independent variables:**

* SAT
* Attendance

The fitted model achieved an **R-squared of 0.565**, meaning the model explains approximately 56.5% of the variation in GPA within this dataset.

Both SAT and Attendance had statistically significant coefficients in the fitted model.

## Technologies & Libraries

* Python
* NumPy
* Pandas
* Statsmodels
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Learning

This project helped develop practical understanding of:

* Dummy variables
* Multiple linear regression
* Categorical data encoding
* Regression coefficients
* R-squared
* Statistical significance
* Data visualisation
* Model-based prediction


## Conclusion

The project demonstrates how categorical information can be transformed into a numerical format and included in a regression model alongside continuous variables. It provides practical experience with statistical modelling and interpreting regression results using Python.
