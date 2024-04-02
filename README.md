# Housing Price Analysis Using Regularized Linear Regression
We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 

The company wants to know:

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
In this assignment, we will

1. Use a hybrid combination of RFE and manual menthods for feature selection.
2. build a linear regression model with ridge and lasso regularization for predicting 'SalePrice', which is the final selling price of a property.
3. Find optimal regularization parameters for each of the methods using Grid search with K-Fold cross validation.
4. Use R-squared score on the test set to evaluate our model
5. Decide which model to go with.

Note that our main criterion of selecting a model would be $R^2$ scores, especially on testing data. 
Further consideration will be given to Lasso if it successfully selects fewer variables in the model.

## Conclusions
The most important features to determine the price of a property are:
1. The overall material and finish of the house
2. First Floor Area
3. Second Floor Area
4. Basement Area

## Technologies Used
- numpy - 1.23.1
- pandas - 1.4.3
- scikit-learn - 1.1.1
