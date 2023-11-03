# Bitcoin Price Prediction using Machine Learning in Python

Machine learning can be a valuable tool for predicting stock market trends and making investment decisions. In this project, we'll explore how to use machine learning to predict whether buying a particular stock will be profitable or not.

## Table of Contents
- [Introduction](#introduction)
- [Importing Libraries](#importing-libraries)
- [Importing Dataset](#importing-dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Development and Evaluation](#model-development-and-evaluation)
- [Conclusion](#conclusion)

## Introduction

In this project, we use Bitcoin price data from 17th July 2014 to 29th December 2022 to build a predictive model. We aim to predict whether buying Bitcoin on a given day will be profitable or not. We will explore various machine learning models and evaluate their performance.

## Importing Libraries

We start by importing the necessary libraries for data handling, visualization, and machine learning. Some of the key libraries used in this project include:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Matplotlib/Seaborn: For data visualization.
- Scikit-learn: For machine learning model development and evaluation.
- XGBoost: For high-accuracy predictions using gradient boosting.

## Importing Dataset

We load the Bitcoin price dataset from a CSV file and perform initial data exploration. The dataset includes Open, High, Low, and Close (OHLC) price data for Bitcoin. We check the dataset's shape and generate basic statistics about the data.

## Exploratory Data Analysis (EDA)

EDA is performed to analyze trends and patterns in Bitcoin prices over time. We visualize the closing prices to understand the price movements. Additionally, we check for outliers in the data using box plots and distribution plots.

## Feature Engineering

Feature engineering is a crucial step in building a machine learning model. In this project, we add new features such as 'day,' 'month,' and 'year' derived from the 'Date' column. We analyze mean prices year-wise using bar plots. We also create features 'is_quarter_end,' 'open-close,' 'low-high,' and 'target' for training our model.

## Model Development and Evaluation

We train different machine learning models, including Logistic Regression, Support Vector Machine, and XGBoost Classifier. The ROC-AUC curve is used as an evaluation metric. We compare the training and validation accuracies of these models. The Logistic Regression model is chosen as it shows better generalization.

## Conclusion

The project demonstrates the application of machine learning in predicting Bitcoin stock market trends. While the models may not outperform simple guessing, this project provides insights into the process of data analysis, feature engineering, and model development in stock price prediction.

This is a basic example of predicting stock market prices, and more advanced models and features can be explored for better predictions.

Feel free to explore and modify this project to improve its performance and achieve more accurate stock market predictions.
