
# Property Price Prediction Project in R  
# RPubs link :  https://rpubs.com/bhargav86/1135935


## Introduction

This project aims to predict property prices using R. It covers various steps from data organization and cleaning to exploratory data analysis (EDA) and modeling. The project utilizes R libraries like tidyverse, validate, and skimr.

## Instructions


## Step-by-Step Guide

### 1.	Organizing and Cleaning the Data
⦁	Subsetting the data into a specific dataset allocated.
⦁	Performing data quality analysis using defined quality checks.

### 2.	Data Quality Analysis
⦁	Integrity check: Ensure data columns adhere to specified criteria.
⦁	Missing value check: Handle missing data via deletion or imputation.
⦁	Uniqueness check: Identify and handle duplicate rows.
⦁	Variable type check: Verify the class of all columns in the dataframe.
⦁	Accuracy check: Remove outliers and ensure data accuracy.
⦁	Special character check: Verify the absence of special characters in columns.
⦁	Quality check for area (mq): Remove entries with area values less than 25.

### 3.	Exploratory Data Analysis (EDA)
⦁	Correlation analysis between price and other variables.
⦁	Visualizations using histograms, scatter plots, bar plots, and box plots.

### 4.	Modeling
⦁	Build multiple models to predict property prices using various explanatory variables.
⦁	Evaluate models and select the most appropriate one based on analysis.


## Project Structure

### 1.	Code Files
⦁	property_price_prediction.R: Contains the R code for the entire project.

### 2.	Data Files
⦁	house-analysis.RDa: Data file containing property details.

### 3.	Output Files
⦁	README.md: This document providing an overview of the project.
⦁	Model outputs, visualizations, and summary statistics generated during the project.



## How to Use

### 1.	Clone the repository.
### 2.	Open property_price_prediction.R in RStudio.
### 3.	Run the code step-by-step to execute the project.

