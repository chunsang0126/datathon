# Cookies Decathlon

## Abstract
In this project, we are trying to solve a problem provided by the company _Cookies Flea_. The goal is to predict the quality of the cookies given some features. 
Our approach is to perform a model that could explain the quality with the least possible error, and do a exhaustive hyperparameter tunning once the best model will be choosen.

* Regression vs Clasification:
Our perspective is that we are faceing a *Regression* problem. Althought the given outcome is an ordinal integer, a classification approach would not properly consider the closeness of the predict value with its response. For example an model that predicts a value of 3 when the correct value was 4 is treated the same as a model which predicts avalue of 22 and the correct value was 4 (both got the classification wrong).

## Data obtaining
For this project we are going to use a cookies dataset stored at Ironhack's Database. 

## Data ingestion and storage
* First, we will obtain the dataset from the database with a library created specifically for this purpose in order to not upload the credentials

## Data cleaning
The preprocessing of the data will include the points below:
* Parsing wrong formated columns
* Hot-encoding categorical columns
* Dropping na-values, outliers  irrelevant or redundant columns, high correlated ones, etc.

## Data Exploratory analysis
In this part, we will check some statistical hypothesis as, for example, that some mixins (g.ex: chocolate) will define the quality of the cookies. 

## Machine Learning modelling
To do.
