# Machine Learning Model - House Price Prediction

## Problem Statement
The goal of this project is to build a machine learning model that predicts house prices based on different property features.

## Dataset Description
The dataset contains information about houses, including:
- Living area size
- Overall quality
- Garage details
- Basement area
- Year built
- Other structural features

## Approach
The project followed a structured machine learning workflow:

1. Loaded the dataset using Pandas
2. Performed data preprocessing
3. Selected important features for prediction
4. Split the dataset into training and testing sets
5. Trained a Linear Regression model
6. Made predictions on test data
7. Evaluated the model using RMSE
8. Visualized results using graphs:
   - Actual vs Predicted values
   - Feature importance

## Model Used
- Linear Regression

## Evaluation
The model was evaluated using Root Mean Squared Error (RMSE).

Final Result:
- RMSE: ~39453

## Results
- The model can predict house prices with reasonable accuracy
- Some predictions are close to actual values, while others show higher error due to limited features

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
