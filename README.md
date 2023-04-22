# SC1015 : Evaluation on whether some anime are worth watching 
## Motivation : 
We would like to find some anime that would be worth watching. However, there are too many options to choose from on the site with which the data has been indirectly retrieved from: myAnimeList.com
So, through this project, we decided to narrow down some anime which can act as sort of a “starting point” for watching.
We are therefore, mostly interested in examining overall popularity, ranking, and favourites, and how these might be affected by other variables, such as genres, episode duration, or number of episodes.

## Goals : 
Our project aims to help people narrow down the anime titles that are worth a watch.

## Dataset Used:
We use the Kraggle "MyAnimeList Dataset".
https://www.kaggle.com/datasets/azathoth42/myanimelist. 

# Overview of Project Outline:
## 1. Exploratory Data Analysis (EDA) 
Explore, visualized and our insights on the EDA 
- Maturity Rating
- Anime Duration
- Genres 
- Studios
- Members

## 2. Regression Models 
- Discussion of the Advantages and disavantages of the different regression models
- Ridge Regression : Is a linear regression model that adds a penalty to the sum of squared coefficients, which shrinks the values of the coefficients towards zero. This helps to reduce the impact of less important features in the model and can improve its overall performance.

- Lasso Regression : Similar to ridge regression, it also adds a penalty to the sum of squared coefficients, but it uses the absolute value of the coefficients instead. This can result in some coefficients being exactly zero, effectively removing those features from the model.

- Elastic Net Regression Model (BEST) : This is a combination of ridge and lasso regression, where both penalties are applied to the sum of squared coefficients. It can be useful when dealing with datasets that have a large number of features, as it can handle situations where there are multiple correlated features by selecting one or a group of features among them.

Metrics Used to conlude the Regression Models
- Mean Squared Error
- R2 Value 
- Cross Validiaton Score on the model

## 3. Classification Models
- Decision Tree Classifier (Best)
- Random Forest Classifier

## Findings/conclusion
We can reliably predict whether an anime is worth watching mainly from the popularity, and score, which in turn can be predicted with genres (most animes that are popular belong the comedy, action and adventure genres), as well as favourites, and episode duration.

We learnt about the different models for regression, as well as one more model for classification. 

# What we learnt from SC1015 Project
## Data Collection : 
- Learn how to be more selective of the dataset that we choose to work with
## Cleaning Our DataSet: 
- Elimination of unecessary data
- Changing string data to integers
- One Hot enocding object types
## EDA & Visualisation: 
- Explored how the different variables were able to affect the Rank and popularity of the anime. 
- See the trend of the anime produced over the years. Genres and Maturity Rating.
- Discovered some very well performing Studios that went under the radar. 
## Machine Learning: 
- Regression Models ( Lasso Regresson, Ridge Regression, Elastic Net Regression). 
- Advantages and disavantages of the different models.
- Visualisation of the models.
- Using Cross Validation to enchance our regression models.  
## Classification Models:
- Random forest model, multiple uncorrelated decision trees amassed into one model. Each prediction tree predicts a class, which acts like a vote. The class with the most votes becomes the overall prediction.
