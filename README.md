# Medical Cost Prediction using Linear Regression

## Overview
This notebook demonstrates how to build a linear regression model to predict medical insurance costs using a dataset of patient information.

## Dataset
The dataset used in this notebook is the `insurance.csv` file. It contains information on medical costs, age, sex, bmi, number of children, smoking habits, and region.

## Libraries Used
*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn

## Data Analysis
*   Exploratory Data Analysis (EDA) was performed to understand the data.
*   Data distributions were visualized using `matplotlib` and `seaborn`.
*   Categorical features were encoded into numerical format.

## Model Training
*   A linear regression model was used to predict medical costs.
*   The data was split into training and testing sets with a 80/20 ratio.

## Model Evaluation
*   The model was evaluated using the R-squared metric.
*   The R-squared value on the training set was 0.75, and on the test set was 0.78.

## Predictive System
*   The predictive system allows you to input patient data (age, sex, bmi, children, smoker, region) and predict medical costs.
*   For example, for the input (31, 1, 25.74, 0, 1, 0) the predicted cost is USD 3761.
