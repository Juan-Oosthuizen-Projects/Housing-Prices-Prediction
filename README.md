# Ames Housing Price Prediction

This project focuses on predicting house sale prices using the Ames Housing dataset. The goal is to apply data science techniques to understand the factors that influence home prices and build predictive models.

## Project Overview
The Ames Housing dataset contains 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa. The objective is to predict the final sale price (`SalePrice`) of each house using these features.

## What I Learned
- Performing **exploratory data analysis (EDA)** to uncover patterns and trends in the data.
- Handling **missing values** and **encoding categorical variables** effectively.
- Creating **new features** through feature engineering to improve predictive performance.
- Building and evaluating **regression models** such as linear regression, random forest, and gradient boosting.
- Understanding the impact of **preprocessing and data cleaning** on model performance.
- Interpreting model results to gain insights into the factors influencing house prices.

## Evaluation Metric
The project uses **Root Mean Squared Error (RMSE) on the logarithm of predicted vs actual sale prices** as the evaluation metric. Log transformation ensures that errors in predicting expensive and inexpensive homes are weighted equally.
