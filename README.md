# Advanced Regression using Ridge and Lasso
In this assignment, we are analyzing housing prices in one region to predict the features that drive the house prices for a company called 'Surprise Housing'. Company would 
For this assignment, I have followed below steps:
Reading and Understanding Data
Data Visualisation
Data Preparation
Feature selection using RFE
Data modeling using Ridge and Lasso
Features that are important in predicting the SalePrice


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market.
Here, based on the data we are building a model to predict the value of the properties.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

## Conclusions
In both Ridge and Lasso, we see similar features driving the SalesPrice -
- OverallQual - Overall material and finish of the house
- GrLivArea - Above grade (ground) living area square feet
- 1stFlrSF, 2ndFlrSF - First and Second floor square feet
  Neighborhood_NoRidge, Neighborhood_NridgHt, Neighborhood_StoneBr , Neighborhood_Crawfor Properties in the neighbourhoods like - Northridge, Northridge Heights, Stone Brook, Crawford
- RoofMatl_WdShngl - Roof Material is Wood Shingles
- GarageCars - Size of the car capacity
- BsmtExposure as Good.
- MasVnrType - Masonry veneer type
- Fireplaces
- TotalBsmtSF - Total Basement Square Feet
- FullBath - Full bathrooms above grade
- GarageArea
- LotArea - Lot size in square feet
- ExterQual - Exterrior Quality
- KitchenQual - Kitchen Quality
- BsmtQual - Basement Quality
- Condition2 as PosN - Near positive off-site feature--park, greenbelt, etc.
- OverallCond - Overall Condition of the house
- BsmtFinSF1 - Type 1 finished square


## Technologies Used
- Numpy 1.24.3
- Pandas 1.5.3
- Seaborn 0.12.2
- statsmodels 0.14.0
- sklearn 1.3.0


## Acknowledgements
- This assignment is part of curriculum for postgraduate program by IIIT-B in Artificial Intelligence and Machine Learning.
- This project uses concepts learned from below modules
  1. Simple Linear Regression
  2. Multiple Linear Regression
  3. Advanced Regression - Ridge and Lasso


## Contact
Created by [@kaspatekajal] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
