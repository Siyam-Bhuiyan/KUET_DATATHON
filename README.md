# KUET Datathon Solution - BitFest 2025

This repository contains the solution for the BitFest Datathon 2025 competition hosted on Kaggle.

## Competition Link

[BitFest Datathon 2025](https://www.kaggle.com/competitions/bitfest-datathon-2025/overview)

## Solution Overview

The solution implements an XGBoost-based regression model with the following key features:

- Text and numerical feature processing pipeline
- Sentiment analysis using TextBlob
- Hyperparameter optimization using Optuna
- Cross-validation for model evaluation

## Technical Stack

- Python
- Key Libraries:
  - XGBoost
  - scikit-learn
  - pandas
  - numpy
  - TextBlob
  - Optuna

## Model Features

- Combined text feature processing using TF-IDF
- Sentiment extraction from text data
- Numerical feature scaling and imputation
- Optimized XGBoost parameters for regression

## Setup and Usage

1. Install required dependencies
2. Place the competition data files (`train.csv` and `test.csv`) in the root directory
3. Run the Jupyter notebook `xgb.ipynb`

## Model Performance

The model is evaluated using Mean Squared Error (MSE) with 5-fold cross-validation.
