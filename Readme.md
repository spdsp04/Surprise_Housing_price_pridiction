# Surprise Housing company:
![1_us8OB_BbS2BCHYQY9Qlv0w](https://user-images.githubusercontent.com/93203186/158931892-a7fc3608-ab7f-46b8-99df-ea420bc3c32a.jpeg)

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
-   Which variables are significant in predicting the price of a house, and
-   How well those variables describe the price of a house.

## Goals of the Case Study
- You are required to model the price of houses with the available independent variables. 
- This model will then be used by the management to understand how exactly the prices vary with the variables.
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
- The model will be a good way for management to understand the pricing dynamics of a new market.
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- And to determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
 - Reading and understanding the data
- Data Visualisation
- Data engineering such as removing null values filling Nan values to                      
- make the data usable for model building
- Data finalisation 
- Data splitting for building the model
- Basic Linear Regression Model using RFE 
- Ridge and Lasso Regression models to regularize the model 
- Residual Analysis of the training data
- Subjective Question 1 and 3

Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions

- We can see that lasso model is more better as the r2 scores are very near to each other which means the model is generalizing very good on unseen test data as well.
- MSSubClass : Identifies the type of dwelling involved in the sale.
- BsmtFullBath	: Basement full bathrooms
- SaleType_Oth	: Type of sale (other)
- Neighborhood_Edwards : Physical locations within Ames city limits (Edwards)
- OverallCond : Rates the overall condition of the house
- MasVnrArea : Masonry veneer area in square feet
- Electrical_FuseF : Electrical system (Fuse_F)
- MSZoning_RH : Identifies the general zoning classification of the sale. (Residential High Density)
- 1stFlrSF : First Floor square feet
- MSZoning_RM : Identifies the general zoning classification of the sale. (Residential Medium Density)
- Optimal values of Lasso is 0.001 and for Ridge it is 10

## Technologies Used
- NumPy version: 1.20.1 
- Pandas version: 1.2.4  
- Seaborn version: 0.11.1
- Sklearn
- Statsmodels
- matplotlib

- Few Commands in jupyter file would take a little time to execute. Please have patience

## Contact
Created by [__Durgesh Chaubey__] - feel free to contact me!
