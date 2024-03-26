# Dry Beans Classification using Logistic Regression

This project uses logistic regression to classify dry beans. The code is written in Python and uses numpy and matplotlib libraries.

## Table of Contents
1. Introduction
2. Data Preprocessing
3. Logistic Regression Model
4. Results
5. PCA Analysis

## Introduction
The goal of this project is to classify dry beans using logistic regression. The dataset contains various features of dry beans which are used to predict the class of the beans.

## Data Preprocessing
The data preprocessing involves transforming the data into a suitable format for the logistic regression model. The `transform_data` function is used to replace the class labels with 'pos' and 'neg'. The 'pos' class corresponds to the class of interest, while all other classes are considered as 'neg'.

## Logistic Regression Model
The logistic regression model is implemented in the `LogisticRegression` class. The class contains methods for training the model (`fit`), making predictions (`predict` and `predict_proba`), and visualizing the cost function over iterations (`plot_cost`). The model uses gradient descent to optimize the weights.

## Results
The results of the model are evaluated using accuracy, F-score, precision, and recall metrics. These metrics provide a comprehensive view of the model's performance.

## PCA Analysis
The code was run with and without Principal Component Analysis (PCA). PCA is a technique used to reduce the dimensionality of the dataset. By reducing the dimensionality, we can speed up the training process and potentially improve the model's performance by removing noise and redundant features.
