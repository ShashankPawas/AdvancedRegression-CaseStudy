# AdvancedRegression-CaseStudy
This assignment contains two parts. Part-I is a programming assignment (to be submitted in a Jupyter Notebook), and Part-II includes subjective questions (to be submitted in a PDF file). 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Assignment Part 1
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
•	Which variables are significant in predicting the price of a house, and
•	How well those variables describe the price of a house.
 
Also, determine the optimal value of lambda for ridge and lasso regression.
 
Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Data Set Provided : train.csv
Data Dictionary : DataDictionary.txt


- Assignment Part 2
Answers for the Subjective Questions to be drafted in PDF format and uploaded.

## Technologies Used
- Jupyter Notebook
- Python
- Libraries
    - numpy
    - Matplotlib
    - seaborn
    - plotly (tried applying - but not used)
    - pandas
    - sklearn
    - statsmodel.api

## Conclusions - Part 1
Following Features / predictor variables have highers influence on SalePrice
- OverallQual : Houses with Rating 'Excellent' and 'Good' Rating for the material and finish
- CentralAir : House with Central air conditioning
- GrLivArea: Houses with higher Above grade (ground) living area square feet
- Neighborhood: House with Physical locations within Ames city limits of 'Somerset' and 'Crawford'
- Functional: Houses with 'Typical Functionality' Home functionality
- Condition1: Houses with 'Normal' Proximity to various conditions or more than one varius conditions.
- TotalBsmtSF: Houses with higher Total square feet of basement area
- OverallCond: Houses with Rating of 'Excellent' Rating for their overall condition
- SaleType : 'New' - Home just constructed and sold
  - This concurrs with our observation from Data Exploration, that Houses which have been Built or remodelled or their Garages Built in last 5 years fetch higher SalePRice.
- MSZoning : Houses in 'FV' Floating Village Residential zone.

Additional Recommendation :
Surprise Housing should also look at collating external factors which can influence the Sale Price of the Houses.
Collating and adding this data to pridict SalePrice, will enhance the Models developed.
Few of the External Factors which commonly affect the Housing Prices:
- Growth of Economy
- Housing Loan Interest Rates
- Employment / Un-Employment statistics
- Mortage Availability
- Market Index

## Conclusion - Part 2
Documented the response to the questions in the PDF and uploaded to GitHub.

## Acknowledgements
  - www.geeksforgeeks.org
  -  https://campus.datacamp.com
  - https://www.wikipedia.org/
  - www.kirenz.com

- This project was based on combination of the reading from various programmer friendly sites and manuals / help guide.

## Contact
Created by [@ShashankPawas] - feel free to contact me!
shashanksp@msn.com
