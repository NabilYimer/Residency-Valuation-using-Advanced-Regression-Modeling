# Residency Valuation using Advanced Regression Modeling

## Overview

This project focuses on predicting residency valuations through advanced regression modeling techniques. It leverages various algorithms, including XGBoost and RandomForest, to predict sale prices based on carefully engineered features.

The project explores and understands datasets through data exploration, performs effective feature engineering to enhance predictive power, and utilizes a range of regression models for accurate valuation predictions. The evaluation metric employed is the root mean squared error (RMSE) on the logarithm of predicted and true sale prices.

## Key Features

- **Data Exploration:** The project delves into exploring and understanding datasets from both training and testing sets.

- **Effective Feature Engineering:** Enhanced predictive power through the creation of features like 'TotalSqFt,' 'HasGarage,' 'HasPool,' 'TotalBathrooms,' 'TotalPorchArea,' and 'HasFireplace.'

- **Data Preprocessing:** Robust preprocessing handles missing values, and one-hot encoding is applied to categorical features.

- **Modeling:** Employed regression models include XGBoost, Neural Networks, Random Forest, Gradient Boosting, Decision Tree, Linear Regression, Lasso, and Ridge.

- **Evaluation Metric:** Model performance is assessed using the root mean squared error (RMSE) on the logarithm of predicted and true sale prices.

## Project Structure

- **`Residency_Valuation.ipynb`:** Jupyter Notebook containing the main project code, including data loading, preprocessing, feature engineering, model training, and evaluation.

- **`train.csv` and `test.csv`:** Datasets used for training and testing machine learning models.

- **`submission.csv`:** CSV file containing the predicted sale prices for the test set.

- **`requirements.txt`:** File specifying the Python dependencies. Install them using:


## Prerequisites

Make sure you have the required libraries installed. You can install them using:

```bash
pip install -r requirements.txt
