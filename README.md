# Exploratory Data Analysis and Linear Regression Analysis on Life Expectancy Factors

## Overview

This project explores the relationship between various factors and life expectancy. It uses exploratory data analysis (EDA) techniques to gain insights into the dataset and then employs linear regression analysis to understand how specific independent variables impact life expectancy.

## Table of Contents

1. [Project Description](#project-description)
2. [Prerequisites](#prerequisites)
3. [Getting Started](#getting-started)
4. [Data Overview](#data-overview)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Linear Regression Analysis](#linear-regression-analysis)
7. [Results and Visualisations](#results-and-visualisations)
8. [Conclusion](#conclusion)
9. [Future Improvements](#future-improvements)

Below are two examples of the linear regression modules produced: 
![LR schooling](https://github.com/Stephanie241/LinearRegressionProject/assets/144491602/ba814c70-a82a-4fc5-8f44-95b50addcc85)
![LR alcohol](https://github.com/Stephanie241/LinearRegressionProject/assets/144491602/3fd41664-9c2d-4540-970e-bf3e7f7a418c)

## Project Description

Life expectancy is a crucial indicator of a country's overall well-being. This project aims to understand the factors that influence life expectancy by performing an in-depth analysis on a dataset containing various health and socio-economic indicators. The primary objectives include:

- Conducting exploratory data analysis (EDA) to uncover patterns and relationships in the data.
- Building linear regression models to quantify the impact of independent variables on life expectancy.
- Visualising the results to communicate insights effectively.

## Prerequisites

Before running the code, ensure you have the following Python packages installed:

- numpy
- pandas
- scikit-learn
- matplotlib

You can install them using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```
## Data Overview
The dataset used in this project contains information about various health and socio-economic factors for different countries, including life expectancy, alcohol consumption, GDP, and more. The data is cleaned and preprocessed to remove missing values.

## Exploratory Data Analysis (EDA)
The EDA phase involves:
- Data visualisation to understand the distribution of variables.
- Correlation analysis to identify relationships between variables.
- Data cleaning and preprocessing.

## Linear Regression Analysis
Linear regression models are built to quantify the impact of independent variables on life expectancy. For each independent variable, the following metrics are calculated:
-Coefficient: The effect of the variable on life expectancy.
-Intercept: The life expectancy when all variables are zero.
-R-squared: The goodness of fit of the model.
-Mean Squared Error (MSE): A measure of model accuracy.

## Results and Visualisations
The results of the linear regression analysis are presented in a structured manner. Visualisations, including scatter plots, are generated to visualise the relationship between independent variables and life expectancy.

## Conclusion
The project provides insights into the factors that impact life expectancy. It demonstrates how data analysis and linear regression can be used to quantify these relationships. The findings can be valuable for policymakers and healthcare professionals.

## Future Improvements
Future enhancements to the project may include:
- More advanced modeling techniques, for example machine learning. 
- Cross-validation to evaluate model performance.
