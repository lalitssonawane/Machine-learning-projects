# Machine-learning-projects
# Predicting House Prices Using Machine Learning

![House](images/house.jpg)

Welcome to my machine learning project focused on predicting house prices using various regression techniques. This project was completed as part of a Kaggle competition and aims to create an accurate predictive model for residential property prices.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Selection](#model-selection)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Introduction

This project dives into the fascinating world of real estate prices prediction using machine learning. The objective is to build a robust model that can accurately estimate house prices based on a variety of features such as square footage, number of bedrooms and bathrooms, location, and more.

## Dataset

The dataset used for this project is sourced from [Kaggle's House Prices competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). It includes both training and test sets, containing information about various residential properties.

## Methodology

1. **Data Preprocessing:** Handling missing values, outliers, and encoding categorical variables.
2. **Exploratory Data Analysis:** Visualizing relationships between features and target variable to gain insights.
3. **Feature Engineering:** Creating new features and transforming existing ones to enhance model performance.
4. **Model Selection:** Evaluating various regression algorithms including Linear Regression, Random Forest, and Gradient Boosting.
5. **Model Evaluation:** Assessing model performance using appropriate metrics on a validation set.

## Exploratory Data Analysis

I conducted a thorough analysis of the dataset, uncovering interesting trends and relationships. Key visualizations include scatter plots to show the correlation between house prices and key features, histograms to visualize data distributions, and heatmaps to display feature correlations.

![Correlation Heatmap](images/correlation_heatmap.png)

## Feature Engineering

To enhance the predictive power of the model, I performed feature engineering. This involved creating interaction terms, transforming skewed features, and extracting meaningful information from categorical variables.

## Model Selection

Several machine learning models were explored, including Linear Regression, Random Forest Regression, and Gradient Boosting Regression. Each model was trained on the preprocessed data, and their performance was compared.

## Model Evaluation

The models were evaluated using mean squared error (MSE) and root mean squared error (RMSE) on a separate validation dataset. The best-performing model was selected for final predictions.

## Conclusion

In conclusion, this project provided valuable insights into the process of predicting house prices using machine learning. By thoroughly analyzing the dataset, performing feature engineering, and selecting an appropriate model, we were able to create a reliable predictive model for house prices.

Feel free to explore the notebooks in the `notebooks` directory to understand the step-by-step process. If you have any questions or feedback, please don't hesitate to reach out.

![Footer](images/footer.png)
