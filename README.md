# Bike Sharing Assignment
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Conclusions
### <font color='darkgreen'>The most important predictor variables:</font>
- `GrLivArea` 
- `OverallQual`
- `TotalBsmtSF`
- `YrBltAndRemod`
- `Total_sqr_footage`
- `Neighborhood`
- `LotArea`
- `GarageArea`

###### <font color='darkgreen'>The Optimal value of alpha for Ridge Regression is : 0.3 and R-Squred on test data :0.85</font>
###### <font color='darkgreen'>The Optimal value of alpha for Lasso Regression is : 0.0001 and R-Squred on test data :0.86</font>

### <font color='darkgreen'>Summary</font>
- `GrLivArea`: Increase of 1 square foot of house area above ground, the price will increase by 1.10 to 1.31 times
- `OverallQual`: Overall material and finish of the house is Very Good or Excellent can increase price by 1.10 to 1.12 times
- `TotalBsmtSF`: Increase of 1 square foot of Total Basement area can increase price by 1.07 to 1.11 times
- `YrBltAndRemod`: Newly built or Remodeled house price can increase by 1.06 to 1.11 times
- `Total_sqr_footage`: Increase of 1 square foot of of total sqr foot, price can increase by 1.10 to 1.11 times
- `Neighborhood`: Having Neighborhood Crawford or Brookside, price can increase by 1.05 to 1.08 times
- `LotArea`: Increase of 1 square foot of Lot area, the price will increase by 1.07 to 1.08 times
- `GarageArea`: Increase of 1 square foot of Lot area, price can increase by 1.05 to 1.06 times


## Technologies Used
Data loading and manipulation libraries
- pandas : Version - 2.0.3

Data visualization libraries
- seaborn : Version - 0.12.2
- matplotlib.pyplot : Version - 3.7.2
- plotly.express : Version - 5.9.0

Stats and LR libraries
- sklearn : Version - 1.3.0
- statsmodels: Version - 0.14.0

Utility
- IPython.display
 - Markdown
 - display
- warnings


## Acknowledgements
This assignment was while doing MS in Artificial Intelligence and Machine Learning from IIIT Bangalore


## Contact
Created by [Bibhuti Ranjan Sinha](https://www.linkedin.com/in/bibhutiranjansinha/)  - feel free to contact me!