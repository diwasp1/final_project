# Final Project - Airline Flight Delay Prediction
Data Science pipeline on-premises and on-the-cloud

This repository contains code for a machine learning project aimed at predicting flight delays. The code is written in Python and uses various libraries for data preprocessing, model training, and evaluation.

## Introduction
The goal of this project is to predict whether a flight will be delayed or not. Here we will explore and preprocess the dataset, train a logistic regression model, and evaluate its performance.

## Getting Started
Before running the code, ensure you have the necessary libraries installed. 

## Data Preprocessing
In this section,the code performs data preprocessing and visualization to better understand the dataset. It involves the following tasks:

1. Extracting data from a compressed file.
2. Combining multiple CSV files into one.
3. Exploring the dataset's basic statistics, including features' means and ranges.
4. Analyzing the distribution of the target variable, which is flight delay.
5. Data visualization to gain insights into the data.

## Model Training and Evaluation
This step focuses on building a machine learning model to predict flight delays. The specific tasks include:
1. Data split into training and testing sets.
2. Training a logistic regression model on the training data.
3. Evaluating the model's performance on the test data.

After running the code, you can expect to have insights into the model's predictive accuracy and other performance metrics.

## Feature Engineering
This section aims to improve the model's performance through feature engineering. Two specific features were added : holidays and weather data.

## Running the Code
There is two jupitor files called 'onpremises.ipynb' and 'oncloud.ipynb'. Use 'onpremises' to run code on local jupitor notebook while use AWS sagemaker to run the 'oncloud.

## Expected Output
Upon running the onpremises code, you can expect to see the following:
1. Exploration of the dataset's basic statistics and visualizations.
2. Training and evaluation of a logistic regression model.
3. Metrics such as confusion matrix, ROC curve, and various statistics (accuracy, precision, recall, sensitivity, specificity).
   
Upon running the oncloud code, you can expect to see the following:
1. learner estimator to build a classifcation model and its performance metrics
2. xgboost estimator to build a classifcation model and its performance metrics
