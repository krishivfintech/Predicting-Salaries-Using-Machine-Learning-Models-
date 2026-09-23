# Predicting Salaries Using Machine Learning Models

This project was completed for DS110 at the New Jersey Institute of Technology.

## Project Overview

The goal of this project was to build machine learning models that predict salary based on factors such as experience, education, job title, skills, certifications, industry, company size, location, and work type.

The project also aimed to identify which factors have the strongest relationship with salary.

## Dataset

The dataset was obtained from Kaggle and contains:

- 250,000 rows
- 10 columns
- Categorical features such as:
  - Job title
  - Education level
  - Industry
  - Company size
  - Location
  - Remote work status
- Numerical features such as:
  - Years of experience
  - Skills count
  - Certifications
  - Salary

## Data Preparation

Before building the models, I:

- Checked the dataset for missing values
- Checked for duplicate records
- Analyzed numerical features using summary statistics
- Examined correlations between variables

The dataset contained no missing values or duplicate rows.

## Machine Learning Models

Three regression models were tested:

### Random Forest Regressor

- R²: 91.45%
- Mean Absolute Error: 8,608

### Decision Tree Regressor

- R²: 94.20%
- Mean Absolute Error: 6,992

### Linear Regression

- R²: 45%
- Mean Absolute Error: 21,708

## Results

The Decision Tree Regressor produced the strongest results in this analysis, achieving the highest R² score and the lowest Mean Absolute Error among the three models tested.

## Skills Demonstrated

- Python
- Machine Learning
- Regression Analysis
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Model Evaluation
- Statistical Analysis

## Challenges

Some of the main challenges included:

- Learning how to implement machine learning models in Python
- Loading and working with a large dataset
- Comparing the performance of different regression models

## Project Presentation

[View the full project presentation](ds110project.pdf)

## Author

Krishiv Cherlo  
Financial Technology Student  
New Jersey Institute of Technology
