# Implementing gradient descent for multiple regression
## Goal
Estimating Multiple Regression Coefficients (Gradient Descent)
## Implementation
* Add a constant column of 1's to a SFrame (or otherwise) to account for the intercept
* Convert an SFrame into a numpy array
* Write a predict_output() function using numpy
* Write a numpy function to compute the derivative of the regression weights with respect to a single feature
* Write gradient descent function to compute the regression weights given an initial weight vector, step size and tolerance.
* Use the gradient descent function to estimate regression weights for multiple features 
## Algorithm
Multiple Linear Regression
## File Description
* .csv file is for dataset
  * kc_house_data.csv is complete dataset file
  * kc_house_train_data.csv is train data file
  * kc_house_test_data.csv is test data file
* .ipynb file is solution of the assignment
