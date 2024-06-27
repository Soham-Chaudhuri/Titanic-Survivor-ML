# Titanic Survival Prediction Model

This repository contains a machine learning model to predict survival on the Titanic based on various features of passengers.

## Overview

The model is built using logistic regression and random forest classifiers, employing preprocessing techniques like standard scaling and one-hot encoding.

## Dataset

The dataset used is the famous Titanic dataset, which contains information about passengers and whether they survived or not.

## Performance Metrics

The model achieved the following performance metrics on a test set:

- **Accuracy:** 95%
- **Precision (Class 0):** 97%
- **Recall (Class 0):** 95%
- **F1-score (Class 0):** 96%
- **Precision (Class 1):** 91%
- **Recall (Class 1):** 95%
- **F1-score (Class 1):** 93%

## Techniques Used

- **Logistic Regression:** Used as a base model.
- **Random Forest:** Utilized for improved performance and robustness.
- **Standard Scaler:** Applied to standardize numerical features.
- **One-Hot Encoding:** Used to encode categorical variables.
- **Pipelines:** Constructed to streamline the preprocessing and modeling steps.

## Files

- **train.csv:** Training dataset used to train the model.
- **test.csv:** Test dataset used to evaluate the model.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn

