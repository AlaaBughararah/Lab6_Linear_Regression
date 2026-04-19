# Machine Learning Lab 6 - Linear Regression

## Overview
This project applies Linear Regression on the Ecommerce Customers dataset. The goal is to predict the yearly amount spent by customers based on different features.

## Dataset
The dataset used is **Ecommerce Customers**, which includes:
- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (target variable)

## Steps Performed
1. Data loading and exploration (head, info, describe)
2. Data cleaning (checking for missing and duplicate values)
3. Exploratory Data Analysis (pairplot, distribution, heatmap)
4. Preparing features (X) and target (y)
5. Splitting data into training and testing sets
6. Training a Linear Regression model
7. Evaluating model performance

## Model Evaluation
The model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The results show that the model performs well, as the predicted values are close to the actual values and residuals are approximately normally distributed.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
