# Prediction using Supervised ML

This is a simple machine learning project that predicts the percentage of marks a student is expected to score based on the number of hours they have studied. The project is based on supervised machine learning techniques, where the model is trained on a dataset with labeled examples (i.e., hours studied vs. marks obtained) to learn the relationship between the input and output variables. Once trained, the model can be used to make predictions on new, unseen data.

## Requirements

This project requires Python 3.0 or later and the following libraries:

numpy
pandas
matplotlib
sklearn

## Dataset

The dataset used in this project is a small dataset with two variables: the number of hours studied and the corresponding percentage of marks obtained by a student. The dataset has been provided in a CSV file data.csv and contains 25 observations.

## Model

The model used in this project is a simple linear regression model, which assumes a linear relationship between the input and output variables. The model is trained using the LinearRegression class from the sklearn library.

## Evaluation

The performance of the model is evaluated using the mean squared error (MSE) and the coefficient of determination (R^2) metrics. These metrics are printed to the console along with the predicted values.
