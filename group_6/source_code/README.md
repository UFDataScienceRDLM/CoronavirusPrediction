# CoronavirusPrediction Ronald DeLuca & Lulu Melhem
Coronavirus Prediction Project

## Setup
Must have python 3.7 and Jupyter Notebook installed with several pip3 packages:
- Scikit-learn
- Tensorflow, Keras
- Scipy
- matplotlib
- xgboost
- Facebook Prophet

Run the *COVID-19 Prediction.ipynb* Jupyter Notebook fully after installing packages and environment to see end results. COVID-19 Prediction.ipynb will pull several CSVs from their respective GitHub repos directly. Other CSVs are located in the data/ folder. 

## Data Set
Source: https://github.com/CSSEGISandData/COVID-19

Daily  Reports are pulled from the repository daily and added to the data folder and will be consolidated into one CSV when the application is ran 

Source: Kaggle COVID-19 Locations & Populations

A data set comprising population and location information of features about populations around the world currently.

Source: Kaggle COVID-19 Open Line List

A data set concerning patient information samples from Wuhan cases.

Source: Johns Hopkins CSSE COVID-19 Global CSVs

Data sets showing global information in a more concise format.

## Pre-Processing the Data 
Information from the local daily report CSV is extracted and processed into a DataFrame. 

The application looks through the data and fills in any missing information and addresses any inconsistencies between the reports. 

The information is output into local CSVs

## Modeling the data 
During the preprocessing step, arrays and DataFrames were initialized and later used as input data for the prediction models

Each model uses the same data (or a slight variation) and time period for its predictions. 

## Evaluating the Results 
Utilizing built-in library functions, several loss functions were used to evaluate each model

An error table at the end of the notebook shows all of the errors for each model