# African Financial Crisis Prediction

## Project Overview

This project focuses on predicting the likelihood of a systemic crisis in 13 African countries based on historical data related to Banking, Debt, Financial, Inflation, and Systemic Crises. The dataset spans from 1860 to 2014 and was obtained from Kaggle.

## Dataset Description

The dataset covers the following countries:
- Algeria
- Angola
- Central African Republic
- Ivory Coast
- Egypt
- Kenya
- Mauritius
- Morocco
- Nigeria
- South Africa
- Tunisia
- Zambia
- Zimbabwe

It includes information on Banking, Debt, Financial, Inflation, and Systemic Crises occurrences.

## Machine Learning Objective

The primary objective of the machine learning model is to predict the likelihood of a systemic crisis emergence. The model utilizes a set of indicators, with a special focus on annual inflation rates.

## Data Cleaning and Preprocessing

- I Cleaned the dataset by addressing missing values.
- I Identified and removed outliers using min and max thresholds.
- I Applied MinMaxScaler to normalize the numerical features.

## Model Training

I Trained the predictive model using the Random Forest Classifier.

## Model Evaluation

Achieved an impressive accuracy of 97.91% (model.score) on the testing dataset.

## Classification Report

Generated a detailed classification report to assess the model's performance.

## Saving the Model

Saved the trained model using the 'joblib' library for future use.

## Steps to Reproduce

To reproduce the project:

1. Clone the repository.
2. Install the required dependencies.
3. Execute the data cleaning and preprocessing scripts.
4. Run the notebook for model training and evaluation.

## Results

Explore the results, key findings, and insights obtained from the model. Feel free to visualize the data and model performance metrics.

## Acknowledgments

- Kaggle for providing the dataset.
- Libraries used: NumPy, Pandas, Scikit-learn, Joblib.


