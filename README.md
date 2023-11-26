# House Price Prediction
> House Price Prediction Case Study Analysis <br>
Author : Gnanaprakash <br>
Date : 26-11-2023

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Overview:

> A US-based housing company named ***Surprise Housing*** has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.

> The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

- Business Problem:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- Data Source: 'house_sale_in_australia.csv' dataset is used here.

## Conclusions
- Based on the score, regression and ridge model are similar but the lasso model goes down
- Coefficients based on ridge model:
	- Positive Coefficients: LotFrontage, LotArea, OverallQual, OverallCond, YearRemodAdd, BsmtFinSF1, TotalBsmtSF, 2ndFlrSF, GrLivArea, Fireplaces, GarageCars, MasVnrArea, WoodDeckSF, OpenPorchSF, Exterior1st_VinylSd, Foundation_PConc, GarageFinish_Unf
	- Negative Coefficients: BsmtUnfSF, BedroomAbvGr, MSSubClass, Year_built_vs_sold, LotShape_Reg, HouseStyle_2Story, Exterior2nd_VinylSd, ExterQual_TA, BsmtQual_TA, BsmtFinType1_Unf, KitchenQual_TA
- There is not much change between the Alpha value and Doubled Alpha value for ridge and lasso model coefficients

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupiter Notebook: 6.5.4
- Python: 3.11.3
- Numpy: 1.24.3
- Pandas: 1.5.3
- Seaborn: 0.12.2
- Matplotlib: 3.7.1
- Sklearn: 1.2.2
- statsmodels: 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [[@Gnana0248](https://github.com/Gnana0248)] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
