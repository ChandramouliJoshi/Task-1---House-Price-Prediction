# Task-1---House-Price-Prediction
Linear Regression was used to predict house prices based on area and room features. Model evaluation and visualization show reasonable predictive performance and error distribution.
House Price Prediction using Linear Regression
Project Overview

This project implements a Linear Regression model to predict house prices based on selected residential features. The model uses:

GrLivArea (above-ground living area in square feet)

BedroomAbvGr (number of bedrooms)

FullBath (number of bathrooms)

The goal is to analyze how these features influence house prices and build a predictive regression model.

Dataset

The project uses two files:

train.csv – Contains input features and the target variable (SalePrice)

test.csv – Contains input features only, used for generating final predictions

Only relevant columns were selected for model training.

Methodology

Data loading and feature selection

Handling missing values

Train–test split (80% training, 20% testing)

Model training using Linear Regression

Model evaluation using Mean Squared Error (MSE) and R² score

Visualization of actual vs predicted values and residual analysis

Results

The model demonstrates reasonable predictive performance using the selected features.
Living area shows the strongest influence on house price, followed by bathrooms and bedrooms.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Conclusion

This project demonstrates the implementation of a regression-based predictive model, including data preprocessing, training, evaluation, and visualization. It provides a clear understanding of how linear regression can be applied to real-world price prediction problems.
