# Real Estate Price Predictor

This repository contains a machine learning project focused on predicting real estate house prices using a Random Forest Regression model. The aim of this project is to provide accurate price predictions based on real estate data.

## Project Overview

The project involves the following steps:

1. **Data Loading and Exploration:**
   - The dataset is loaded from a CSV file, and exploratory data analysis (EDA) is performed to understand the data structure and distribution.
   - Histograms and correlation matrices are utilized to visualize relationships between features.

2. **Data Preprocessing:**
   - Feature scaling and imputation of missing values are handled using a machine learning pipeline.
   - The dataset is split into training and testing sets.

3. **Model Selection and Training:**
   - Multiple regression models are considered, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
   - The Random Forest Regressor is selected and trained on the dataset.

4. **Model Evaluation:**
   - The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and Root Mean Square Error (RMSE).
   - Cross-validation is used to assess the model's reliability.

5. **Model Saving and Testing:**
   - The trained model is saved for future predictions using `joblib`.
   - The model is tested on the test dataset to check its performance.

## Files Included

- **Attributes Information.txt**: Contains detailed information about the features used in the dataset.
- **data.csv**: The raw dataset used for training and testing the model.
- **Real_Estate.joblib**: The saved Random Forest Regression model for making predictions.
- **Model Scores.txt**: Includes the Root Mean Square Error (RMSE) scores for each model tested.
- **Real_Estate_NB.ipynb**: The Jupyter Notebook containing the complete code and analysis for the project.

## Results

- The Random Forest Regression model achieved a low RMSE, indicating high predictive accuracy.
- The model's performance can be evaluated further in the `Model Scores.txt` file.


