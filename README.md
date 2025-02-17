# Installation
The code should run with no issues using Python versions 3.*. The specific packages used 
in this project mainly are pandas, numpy, matplotlib,seaborn and sklearn for the purposes of data cleaning 
and manipulation, data visualization and modeling respectively.

pip install -r requirements.txt

# udacity_datascience
Udacity Training, submission of projects on Data Science  course

# **GDP Growth Prediction using Linear Regression**

## Overview

This project uses a linear regression model to predict GDP growth based on population growth 
and inflation data for the United States from 2000 to 2015. The dataset includes annual figures for 
population growth, GDP growth, and inflation.

Data Source
The data is stored in cleanData.csv, containing 16 rows of annual economic indicators from 2000 to 2015.

## Project Structure

rawData.csv : 
This is the raw data fetched from https://databank.worldbank.org/country/USA/556d8fa6/Popular_countries#
containing the data from 2000 to 2015 with values of 

        Population growth (annual %)
        GDP growth (annual %)
        Inflation, GDP deflator (annual %)
        Year(2000 to 2015)

cleanData.csv: This file contains the cleansed data after converting columns into rows using pandas.

gdp_growthPrediction.ipynb: Python script for Exploratory data analysis(EDA) 
and Linear Regression Model training, Model Evaluation & Model Testing
README.md: This file provided project information

## **Dependencies**

    pandas
    numpy
    scikit-learn
    matplotlib
    Usage
Ensure all dependencies are installed.
Run the gdp_growthPrediction.ipynb script

## Results

The main aim of this project is to create a blog post on medium to answer few business questions,medium blog post is avaliable in below link

https://medium.com/@narendrakuppala.ai/from-data-pipes-to-economic-insights-a-data-engineers-journey-into-data-science-0ad3837d0c7a


##  Acknowledgements

Data is fetched/gathered/assesed from https://databank.worldbank.org/country/USA/556d8fa6/Popular_countries# for United States of America for the period between 2000 to 2015
