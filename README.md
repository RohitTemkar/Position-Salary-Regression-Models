﻿# Position Salary Regression Models

This repository contains several regression models implemented to predict position salaries based on the "Position_Salaries.csv" dataset.

## Models Implemented

The following regression models are included:

- **Polynomial Regression**[cite: 1]: A model that uses polynomial terms to capture non-linear relationships between position level and salary.
- **Support Vector Regression (SVR)**: A non-linear regression model that uses support vector machines. It requires feature scaling.
- **Decision Tree Regression**: A model that partitions the data into subsets to make predictions.
- **Random Forest Regression**: An ensemble learning method that operates by constructing a multitude of decision trees at training time and outputting the mean prediction of the individual trees.

## Dataset

The dataset used is "Position_Salaries.csv". It contains information on position level and corresponding salaries.

## Files Included

- `Position_Salaries.csv`: The dataset.
- `polynomial_regression.ipynb`: Jupyter Notebook for Polynomial Regression.
- `support_vector_regression.ipynb`: Jupyter Notebook for Support Vector Regression.
- `decision_tree_regression.ipynb`: Jupyter Notebook for Decision Tree Regression.
- `random_forest_regression.ipynb`: Jupyter Notebook for Random Forest Regression.
- `README.md`: This file.

## Usage

Each Jupyter Notebook (`.ipynb`) contains the code and explanations for the corresponding regression model. To run the code, you will need to have Python installed, along with the libraries:

- numpy
- matplotlib
- pandas
- scikit-learn
