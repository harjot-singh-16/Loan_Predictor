# Loan Prediction using Machine Learning
This repository contains a project that demonstrates a machine learning approach to predicting loan approval status. The project involves exploring the dataset, preprocessing the data, building and evaluating machine learning models, and making predictions.

## Introduction
The objective of this project is to predict whether a loan application will be approved or not based on various features provided in the dataset. This is a binary classification problem, and we will explore different machine learning algorithms to achieve accurate predictions.

## Dataset
The dataset used in this project is provided in the `train.csv` and `test.csv` files. It includes features like gender, marital status, income, credit history, loan amount, etc. The goal is to build a model that can predict the loan approval status based on these features.

## Project Structure


|-- data #####
|   |-- train.csv
|   |-- test.csv
|   |-- sample_submission.csv
|-- notebooks
|   |-- model.ipynb
|-- models
|   |-- Logistic
|   |-- DecisionTree
|   |-- RandomForest
|   |-- ANN

First we explored the dataset's features, distributions, relationships, and trends. Visualizations are created using libraries like Pandas, Seaborn, and Matplotlib. Data preprocessing steps are carried out carefully. These steps include handling missing values, encoding categorical variables, and creating new features if needed.
The Model building focuses on building and evaluating machine learning models for loan prediction. Different algorithms like Logistic Regression, Decision Trees, and Neural Networks are explored. Model evaluation metrics and visualizations are included.

