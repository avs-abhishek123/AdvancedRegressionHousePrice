# Project Name
> **Problem Statement**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and

2. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The solution is divided into the following sections:
- Data Understanding and Exploration
- Data cleaning
- Data preparation
- Model building and evaluation
- Observation and inference

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The below mentioned variables are significant in predicting the price
    - LotArea------------- Lot size in square feet
    - OverallQual--------Rates the overall material and finish of the house
    - OverallCond-------Rates the overall condition of the house
    - YearBuilt-------- ---Original construction date
    - BsmtFinSF1-------Type 1 finished square feet
    - TotalBsmtSF------Total square feet of basement area
    - GrLivArea----------Above grade (ground) living area square feet
    - TotRmsAbvGrd---Total rooms above grade (does not include bathrooms)
    - Street_Pave-------Pave road access to property
    - RoofMatl_Metal--Roof material_Metal
- How well Ridge Regression is descibing the price of house?
    - R2 Score of Ridge Regression on training dataset is 88%
    - R2 Score of Ridge Regression on test dataset is 87%
- How well Lasso Regression is descibing the price of house?
    - R2 Score of Lasso Regression on training dataset is 88%
    - R2 Score of Lasso Regression on test dataset is 86%


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.6.9
- Numpy - version 1.21.5
- Pandas - version 1.3.5
- Seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on Upgrad's Tutorial.


## Contact
Created by [@shrutipandit707] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->