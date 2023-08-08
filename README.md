# Advanced Regression Assignment
> Predicting Price of House and decide whether to invest
> (Usage of Linear Regression and Regularization)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?
    
    A US-based housing company named Surprise Housing has decided to enter the Australian market.

    The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

    The data is provided in the CSV file below.   The company is looking at prospective properties to buy to enter the market.

    You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.   The company wants to know:

    Which variables are significant in predicting the price of a house, and
    How well those variables describe the price of a house.
    Also, determine the optimal value of lambda for ridge and lasso regression.


- What is the business probem that your project is trying to solve?

    You are required to model the price of houses with the available independent variables.

    This model will then be used by the management to understand how exactly the prices vary with the variables.

    They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


- What is the dataset that is being used?

    - Australian Housing market dataset (train.csv) and Data dictionary was provided to student.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1) Lasso regression model was chosen based on optimal value, simplicity, lower number of features, high R-squared and low Mean Squared Error.

2) The following predictor variables (Lasso regression) are significant in predicting House prices:
    TotalAreaSF, OverallQual, GrLivArea, OverallCond, YearBuilt, Neighborhood_Crawfor, BsmtFinSF1, BsmtQual_Gd, KitchenQual_TA and KitchenQual_TA.

3) An accompanying PDF has answers to Part-2 Subjective questions (per assignment)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - Version 1.23.5
- pandas - Version 1.5.3
- seaborn - Version 0.12.2
- matplotlib - Version 3.7.0
- sklearn - Version 1.2.1
- statsmodels - Version 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Liverpool John Moores University & IIIT Bangalore
AI/ML MSc. Degree assignment on Advanced Regression assigment 


## Contact
Advanced Regression Assignment <br>
by Karthik Jayaraman [@karthikjram] (https://www.github.com/karthikjram) - feel free to contact me!



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->