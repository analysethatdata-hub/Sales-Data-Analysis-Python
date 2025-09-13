# Sales-Data-Analysis-Python
This is an analysis of retail data
# Apparel Python Project

## Project Overview

**Project Title**: Retail Sales Analysis  
**Level**: Beginner  
**Dataframe**: `apparel dataframe`

This project is designed to demonstrate python skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves reading a csv file to create an apparel dataframe with pandas and performing exploratory data analysis (EDA)

## Objectives

1. **Import csv into pandas**: Read csv file into pandas,create a dataframe.
2. **Data Cleaning**: Identify and remove any records with missing or null values and create proper datatype formats.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.
4. **Business Analysis**: Apply advanced data skills to measure growth,changes in sales and quantities.

## Project Structure

### 1. Dataframe Setup

- **Dataframe**: The project starts by creating a dataframe.


```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
df=pd.read_csv('sales_data.csv')
```

### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Sales_Rep Count**: Find out how many unique sales rep are in the dataset.
- **Region Count**: Identify all unique regions in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.
- **Product Category Count**: Find out how many unique product categories are in the dataset.
- **Customer type Count**: Identify all unique citiescustomer types in the dataset.
- **Sales Channel**: Identify all unique sales channels in the dataset.
- **Payment Method Count**: Identify all unique payment methods in the dataset.


### 3. Analysis & Findings

- **Sales Trends**: Monthly analysis shows variations a lot of variation in sales.
- **Customer Insights**: The analysis identifies the top-spending customers and the most popular product categories.
- **Seasonality**:None was identified due to the variations in the monthly analysis.


## Conclusion

This project serves as a introduction to python for data analysis, covering dataframe setup, data cleaning and exploratory data analysis. 

## Author - analysethatdata

