# AMEX: Credit Default Preduiction

## Project Overview
The convenience of credit cards has become an indispensable aspect of modern life, facilitating daily purchases without the need to carry large amounts of cash. However, as credit card issuers extend credit to customers, the challenge of predicting the likelihood of payment default arises. This is a complex problem that has been addressed by many existing solutions, with opportunities for further improvements.
In this project, I present the results of the American Express - Default Prediction Kaggle competition, an data science competition hosted on the Kaggle platform by American Express. The objective of the competition was to predict which credit card customers were likely to default on their payments.
## Objectives
* In this competition, I built models to predict credit default. Specifically, I leveraged an industrial scale data set to build a machine learning model that challenges the current model in production. Training, validation, and testing datasets include time-series behavioral data and anonymized customer profile information.
## Methodology
- Data Wrangling - `Dropped misssing or null salaries values in the dataset, replacing the Years of Experience to the mean and analyzed/removed outliers.`
- Exploratory Data Analysis - `Analyzed the data and summarized the main characteristics.`
- Data Visualization - `Used boxplot, bar plot, scatter plot and violin plot to visualize the data and it's characteristics.`
- Machine Learning Algorithms - ` The models trained were: Lasso, ElasticNet, Decision Tree Regressor, KNeighbors Regressor, Random Forest Regressor and Gradient Boosting Regressor.`
- Evaluation Metrics Used - `Mean Absolute Error (MAE) and R-squared`

## Conclusions
Gradient Boosting Regressor Model resulted in a better performace applying prepocessing steps (Standard Scale, One Hot Encoding and Ordinal Coding) for specific features. The Model Evaluation resulted: **Mean Absolute Error of 13,612.26 and R-squared of 75.8%.**
