# Titanic-Survival-Prediction
This project predicts Titanic passenger survival based on features identified in the [Exploratory Data Analysis(EDA)](https://github.com/Leelavathi-R/Titanic-Survival-EDA). The key influencing factors include Age, Sex, Fare, and Pclass.

# Dataset
The Titanic dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset) as part of Titanic - Machine Learning from Disaster Kaggle [competition](https://www.kaggle.com/competitions/titanic/overview)

## Requirements
* python >= 3.0
* Pandas
* Sklearn

## Data Cleaning
Cleaning steps:
* Handling missing values.
* Dropping duplicate rows.
* Duplicate columns check.
* Data Format check
* Outlier check
* Changing Datatype

## Feature Engineering
Created two new features to improve the model performance:
* 'AgeGroup'
* 'FamilySize'

## Model Building
* The dataset was split into 80% training and 20% testing sets.
* A logistic regression model was developed.
* Achieved an accuracy of 82%.









  
