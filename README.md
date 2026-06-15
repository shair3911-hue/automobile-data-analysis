# Automobile Data Analysis

## Overview
End-to-end data analysis project on the UCI Automobile Dataset covering 
data acquisition, cleaning, transformation, exploratory analysis, 
model development and evaluation using Python.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Link:** https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data
- **Size:** 205 rows × 26 features
- **Domain:** Automotive / Insurance Risk Rating

## Project Workflow

### 1. Data Importing
- Loaded dataset directly from UCI repository
- Assigned meaningful column headers
- Explored basic data structure and types

### 2. Data Wrangling
- Identified 7 columns with missing values
- Replaced `?` placeholders with `NaN`
- Imputed missing numerics with column mean
- Imputed missing categoricals with mode
- Removed rows with missing target variable (price)
- Corrected data types across all columns

### 3. Data Transformation & Feature Engineering
- Converted fuel consumption units from mpg → L/100km
- Normalized length, width and height using Simple Feature Scaling
- Binned horsepower into Low / Medium / High categories
- One-Hot Encoded fuel-type and aspiration columns

### 4. Exploratory Data Analysis *(upcoming)*
- Correlation analysis between features and price
- Distribution analysis of key variables
- Relationship between horsepower, engine size and price

### 5. Model Development *(upcoming)*
- Linear regression for price prediction
- Multiple regression with feature selection
- Polynomial regression for non-linear relationships
- Ridge regression

### 6. Model Evaluation *(upcoming)*
- Cross-validation
- R² and MSE evaluation
- Model comparison and selection

## Key Findings
- Most cars fall in the low horsepower range (48–119)
- 7 out of 26 columns contained missing values
- 84% of sedans in the dataset have four doors
- Strong correlation expected between engine size and price

## Tech Stack
- **Python** 3.x
- **Pandas** — data manipulation and cleaning
- **NumPy** — numerical operations
- **Matplotlib** — data visualisation
- **Scikit-learn** — machine learning models *(upcoming)*

## Repository Structure
