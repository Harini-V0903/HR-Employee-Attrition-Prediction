# HR-Employee-Attrition-Prediction

This project focuses on analyzing employee data and predicting whether an employee is likely to leave the company using Logistic Regression.


Project Overview

Employee attrition is a major concern for organizations. This project uses machine learning techniques to:
Analyze HR dataset
Identify patterns in employee behavior
Predict whether an employee will leave the company

Technologies Used
Python 
Pandas (Data Processing)
Scikit-learn (Machine Learning)
NumPy
Jupyter Notebook

Dataset
The dataset contains employee details such as:
Satisfaction Level
Last Evaluation
Number of Projects
Average Monthly Hours
Time Spent in Company
Work Accident
Promotion in Last 5 Years
Department
Salary
Target Variable: left (0 = Stay, 1 = Leave)

Workflow
Load dataset
Preprocess data (One-Hot Encoding)
Split into training & testing sets
Train Logistic Regression model
Evaluate accuracy

Model Used
Logistic Regression
Logistic Regression is used for binary classification problems

Manual Prediction Logic
The project also includes a manual implementation of prediction using:
Model coefficients
Intercept
Sigmoid function
This helps in understanding how predictions are made internally.

Results
Model accuracy is evaluated using test data
Provides insight into employee attrition patterns
