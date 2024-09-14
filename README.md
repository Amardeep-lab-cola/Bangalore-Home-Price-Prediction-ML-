# Bangalore Home Price Prediction

This repository contains a project aimed at predicting home prices in Bangalore using various machine learning techniques. The project involves data cleaning, exploratory data analysis, model selection, and evaluation using K-fold cross-validation to determine the best model.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
- [K-Fold Cross-Validation](#k-fold-cross-validation)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Predicting home prices is a crucial task in real estate, helping both buyers and sellers make informed decisions. This project aims to build a predictive model for home prices in Bangalore using various machine learning techniques.

## Dataset

The dataset used in this project contains information about various homes in Bangalore, including features such as location, size, total square feet, number of bathrooms, and the price.

## Data Cleaning

Data cleaning is an essential step to ensure the quality and reliability of the data. The following steps were taken:
- Handling missing values.
- Removing duplicates.
- Converting categorical data to numerical data (including one-hot encoding for location).
- Normalizing and scaling the data.
- Removing outliers(using bathroom feature and others also).

### One-Hot Encoding for Location

Locations in the dataset were encoded using one-hot encoding to convert categorical location data into a numerical format suitable for machine learning models. This ensures that each location is represented by a binary vector, making it easier for the model to process.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand the distribution and relationships of the data. Key visualizations and insights include:
- Distribution of home prices.
- Correlation between different features and the price.
- Visualizing the data using scatter plots.

## Machine Learning Models

Several machine learning models were applied to predict home prices:
- Linear Regression
- Decision Tree
- Lasso

## K-Fold Cross-Validation

K-Fold Cross-Validation was used to evaluate the performance of the models. This technique helps in assessing the model's ability to generalize to unseen data. The dataset was divided into k subsets, and the model was trained and tested k times, each time using a different subset as the test set and the remaining as the training set.

## Results

The performance of each model was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). The best-performing model was found to be Linear Regression , which achieved a cross validation score of 87%.

## Conclusion

This project demonstrates the application of machine learning techniques in predicting home prices. The use of K-Fold Cross-Validation ensures that the model generalizes well to new data. The results indicate that Linear Regression  is the most effective model for this dataset.
