# Titanic Survival Prediction

This repository contains a Jupyter notebook for predicting the survival of passengers on the Titanic using various machine learning models.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Features](#features)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction
The goal of this project is to predict whether a passenger on the Titanic survived or not based on various features such as age, sex, ticket class, fare, and more. This is a classic binary classification problem often used in machine learning.

## Dataset
The dataset used for this project is the Titanic dataset provided by Kaggle. It contains information about the passengers on the Titanic, including:
- `Pclass`: Passenger class
- `Sex`: Sex of the passenger
- `Age`: Age of the passenger
- `Fare`: Fare paid by the passenger
- `Embarked`: Port of embarkation
- `Survived`: Survival status (target variable)

## Installation
To run the notebook, you need to have Python and the following packages installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lazypredict


## Features

This Jupyter notebook provides a comprehensive guide to building and evaluating machine learning models using Python. It covers the following steps and features:

- Data loading and exploration
- Data preprocessing:
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling

- Model training and evaluation for the following classifiers:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

- Comparison of multiple models using LazyPredict for quick baseline model evaluation.

## Models

The notebook utilizes the following machine learning models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Additionally, LazyPredict library is employed to quickly build and evaluate a variety of baseline models.

## Evaluation

The models are evaluated using the following metrics:

- Accuracy
- Confusion Matrix
- Classification Report

## Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request with a detailed description of your changes.
