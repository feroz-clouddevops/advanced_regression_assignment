# Advanced Regression Assignment
> This repository holds code to build advanced regression models for the prediction of house sale prices by a US-based company.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- This assignment attempts to identify ‘key’ features that contribute to the house sale prices from the given dataset.
- It creates advanced Regression Models using Ridge and Lasso regularisation to predict the prices of houses.
- It also includes a 'Subjective Questions and Answers.pdf' with answers to subjective questions, that are part of the assignment evaluation.
- This project is an assignment submission for Upgrad AI & ML course.
- The dataset used is the `train.csv(attached)` dataset provided by upgrad.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels

## Conclusions
1. We will proceed with lasso regression for this dataset, since it provides highest R2 score of 86.37 % on test dataset and the lowest RMSE values.
2. The optimum value of lambda for Ridge regression model is 2.0.
3. The optimum value of lambda for Lasso regression model is 100.
4. Since we are proceeding with Lasso Regression, the most significant variables in predicting price of the house are as follows:
    - LotArea: Lot size in square feet
    - OverallQual: Overall material and finish of the house
    - OverallCond: Overall condition of the house
    - YearBuilt: Original construction date
    - BsmtFinSF1: Type 1 finished square feet
    - TotalBsmtSF: Total square feet of basement area
    - 1stFlrSF: First Floor square feet.
    - GrLivArea: Above grade (ground) living area square feet
    - BedroomAbvGr: Bedrooms above grade
    - TotRmsAbvGrd: Total rooms above grade
    - ExterQual_Fa: Evaluates the quality of the material on the exterior (fair)
    - ExterQual_Gd: Evaluates the quality of the material on the exterior (good)
    - ExterQual_TA: Evaluates the quality of the material on the exterior (typical/average)
    - Functional_Sev: Home functionality - Severely Damaged (negative relationship)
    - GarageType_BuiltIn: Garage location - Builtin garage
5. How well these variables describe the price of house:
    - As per the R2 score, we can see that the above variables describe around 86.37% (R2 score of test data) of variation in the price of the house.