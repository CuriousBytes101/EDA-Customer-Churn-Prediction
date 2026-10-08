# EDA - Customer Churn Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a customer churn dataset using Python.

The main goal of this analysis is to understand customer characteristics, service usage, contract types, payment methods, and other factors that may be related to customer churn.

## Objectives

- Understand the customer dataset
- Explore customer characteristics
- Analyze the distribution of categorical and numerical variables
- Study customer churn patterns
- Identify factors that may be related to churn
- Create visualizations to understand the data

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains customer information such as:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn

## EDA Performed

### 1. Data Understanding

- Loaded the dataset using Pandas
- Checked the dataset structure
- Examined columns and data types
- Checked unique values
- Reviewed the distribution of different variables

### 2. Data Cleaning

- Checked for missing values
- Converted required columns into appropriate formats
- Converted the SeniorCitizen values from 0 and 1 to No and Yes for easier interpretation
- Checked categorical values

### 3. Univariate Analysis

Analyzed individual variables using count plots and other visualizations.

Categorical variables analyzed include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Churn

### 4. Churn Analysis

Analyzed customer churn across different customer and service-related variables using visualizations.

Variables analyzed against churn include:

- Senior Citizen
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method

## Key Insights

- Around 26.54% of customers have churned, while the majority of customers have stayed.
- Gender does not seem to have much effect on customer churn.
- Senior citizens have a higher churn proportion compared to non-senior citizens.
- Customers with lower tenure are more likely to churn, while long-term customers tend to stay.
- Month-to-month customers have more churn compared with one-year and two-year contract customers.
- Customers who do not use services such as Online Security, Online Backup and Tech Support show more churn.
- Electronic check users show comparatively higher churn than other payment methods.
- Contract type, tenure, payment method and additional services appear to be important factors related to customer churn.

## Project Structure

```text
EDA-Customer-Churn-Prediction/
│
├── Customer Churn.csv
├── Customer_Churn_Analysis.ipynb
└── README.md
