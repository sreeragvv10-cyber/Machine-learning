# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques and the California Housing Dataset.

The project uses Python and Scikit-learn to build a Linear Regression model that predicts median house values based on different housing features such as location, income, number of rooms, bedrooms, population, and housing age.

The main objective is to develop a machine learning model that can estimate house prices and evaluate its performance using standard regression metrics.

## 🎯 Project Objectives

- Analyze the California Housing Dataset.
- Perform data cleaning and preprocessing.
- Handle missing values.
- Explore relationships between housing features.
- Build a Machine Learning model using Linear Regression.
- Predict median house values.
- Evaluate model performance using regression metrics.
- Compare actual and predicted house prices.

## 📂 Dataset Information

**Dataset:** California Housing Dataset

- Total Records: 20,640
- Total Features: 10
- Missing Values: 207 (in `total_bedrooms`)
- Duplicate Records: 0

### Dataset Features

| Feature | Description |
|---|---|
| longitude | Longitude of the location |
| latitude | Latitude of the location |
| housing_median_age | Median age of houses |
| total_rooms | Total number of rooms |
| total_bedrooms | Total number of bedrooms |
| population | Population of the area |
| households | Number of households |
| median_income | Median income of the area |
| median_house_value | Median house value (Target) |
| ocean_proximity | Distance/location relative to the ocean |

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

1. Imported the dataset using Pandas.
2. Explored the dataset using `head()`, `tail()`, `info()`, and `describe()`.
3. Checked for missing values.
4. Checked for duplicate records.
5. Handled missing values in `total_bedrooms` using median imputation.
6. Visualized house price distribution.
7. Created a correlation heatmap.
8. Separated independent variables (X) and dependent variable (y).
