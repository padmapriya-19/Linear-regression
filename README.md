# Boston Housing Price Prediction using Linear Regression

## Project Overview

This project builds a Machine Learning model to predict house prices using the Boston Housing dataset.
The model uses **Linear Regression** to estimate the median value of houses based on selected features.

The dataset is loaded from an online source and the model is trained and tested using the Scikit-Learn library.

## Dataset

Dataset used: Boston Housing Dataset
Source: https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv

The dataset contains information about housing areas in Boston including factors like number of rooms, population status, and student-teacher ratio.

## Features Used

The following features are used to predict house prices:

* **rm** – Average number of rooms per dwelling
* **lstat** – Percentage of lower income population
* **ptratio** – Student-teacher ratio

## Target Variable

* **medv** – Median value of owner-occupied homes

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Machine Learning Model

The project uses **Linear Regression** for predicting house prices.

Linear Regression is a supervised learning algorithm used to predict continuous numerical values by finding the relationship between independent variables and a dependent variable.

## Steps in the Project

1. Import required libraries
2. Load the dataset using Pandas
3. Check dataset structure and missing values
4. Select features and target variable
5. Split data into training and testing sets
6. Train the Linear Regression model
7. Predict house prices
8. Evaluate model using Mean Squared Error and R² score
9. Visualize Actual vs Predicted values using a scatter plot

## Evaluation Metrics

Two metrics are used to evaluate model performance:

* **Mean Squared Error (MSE)** – Measures the average squared difference between predicted and actual values.
* **R² Score** – Indicates how well the model explains the variance in the data.

## Visualization

A scatter plot is used to compare actual house prices with predicted prices.

## Output

The program prints:

* Mean Squared Error
* R² Score

And displays a graph showing the relationship between actual and predicted house prices.

## How to Run the Project

1. Install Python
2. Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Python file

python housing_prediction.py

## Author

B.Tech Computer Science Student
Interested in Artificial Intelligence and Machine Learning
