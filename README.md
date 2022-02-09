# Surprise Housing Prediction
In this segment we have come across a situation where a U.S. based housing company called as Surprise Housing wants to enter australian market. So, this company wants to utilise data analytics to buy the houses at lower prise and flip it to higher price. Thus the company has decided to come up with a good business plan utilizing the existing dataset related to sales of houses, where it can come with some approch to understand which would be influencing factors on price of house.

**Business Goal**
So we need to design a regression model, using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

**Key Factors of Interest**
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

**Steps to build Advanced Regression Model**
- Loading Data Set
- Getting overview of Data Set
- Data Preprocessing and Data Cleaning
- Data Visualization (EDA)
- Further Data Processing
- Model Buidling and Evaluation
- Ridge Regression
- Lasso Regression

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'train.csv' file uploaded in the repository.

The company is looking at prospective properties to buy to enter the market. This repository builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

Using GridSearchCV the model arrives at a final optimum lambda to determine the house prices using ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We will use lasso for final model prediction since:
- The scores are higher and consistent
- Model is simpler than ridge (less number of variables).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas  - v0.25.1 
- Numpy - v1.16.5
- Matplotlib - v3.3.2
- Seaborn - v0.9.0
- Sklearn - v0.21.3
- Statsmodel - v0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by upgrad Advanced Regression Assignment
- References: https://scikit-learn.org/stable/modules/feature_selection.html


## Contact
Created by [@rashmiaab] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
