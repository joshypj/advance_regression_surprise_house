# Advanced Regression - Surprise Housing
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 
The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
* ### Problem Statement
    A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 
   
 * ### Buisiness Objectives
The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house

 * #### Scope of the Case study : 
   You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Summary of the analysis and key take-aways
  - Step 1: Loading and Understanding the Data
  - Step 2: Data Analysis and Data Cleaning
  - Step 3: Data Modelling
  - Step 4: Model Evaluation
## Conclusions

 - Key attributes which which affecting the House Pricing are:
 - #### Business Objectives
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house

#### The variables influencing the Price of the House
- OverallQual : Houses with Rating 'Excellent' and 'Good' Rating for the  material and finish
- GrLivArea: Houses with higher Above grade (ground) living area square feet
- Neighborhood: House with Physical locations within Ames city limits of 'Somerset' and 'Crawford'
- Functional: Houses with 'Typical Functionality' Home functionality
- Condition1: Houses with 'Normal' Proximity to various conditions or more than one varius conditions.
- MSZoning: Identifies the general zoning classification of the sale.
- TotalBsmtSF: Houses with higher Total square feet of basement area
- OverallCond: Houses with Rating of 'Excellent' Rating for their overall condition
- SaleCondition: Condition of sale
- MSZoning : Houses in 'FV' Floating Village Residential zone.
#### Insight from Regularization
- Both lasso and ridge doign a good job in addressing the regularization


    
 

     
 - Detailed conclusion mentioned in the Notebook file
  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.24.1
- pandas - 1.3.4
- matplotlib.pyplot - 3.5.2
- seaborn - 0.12.2
- statmodels - 0.13.5
- sklearn - 0.0.post1


## Acknowledgements
- This project perfored as part of the IIT-B /Upgrad EDG Program



## Contact
Created by Joshy PJ 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
