# CoronavirusPrediction
Coronavirus Prediction Project

## Data Set
Source: https://github.com/CSSEGISandData/COVID-19

Daily  Reports are pulled from the repository daily and store locally in the the data forlder 

The reports are consolidated into one csv wen the application is ran 

## Pre-Processing the Data 
Information from the local daily report csv is extracted and into a DataFrame. 

The application reviews the data and fills in any missing information and addresses any inconsistsencies between the reports 

The information is outputted into one local CSV

## Modeling the data 
During the preprocessing step, arrays and DataFrames were nitialized and later used as input data for the prediction models

Each model uses the same data (or a slight variation) and time period for its predictions. 

## Evaluating the Results 
Utilizing built-in library functions, several loss functions were used to evaluate each model

An error table at the end of the notebook shows all of the errors for each model
