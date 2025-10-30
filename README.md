# SALES-DATA-PYTHON-ANALYSIS
This shows python data analysis skills using Pandas and Matplotlib libraries.

# PROJECT OVERVIEW

The Sales data analysis project is designed to explore and analyzie key insights from a dataset containing different sales informations about payment method, total number of sales and order etc.By applying data analysis and visualization technique using pandas and matplotlib.The project aims to uncover key patterns within the dataset.

## Objective
-Clean and preprocess the dataset to ensure data integrity.

-Analyze the distribution of sales.

-Examine the standard deviation of revenue.

-Identify key insights that would help sales improvement.

## Expected outcome
1.A Comprehensive understanding of the dataset through summary satistics.

2.Identification of any factor affecting sales.

3.Actionable insights for decision making in sales.

## Key Questions
1. What was the Most Preferred Payment Method?
   
2. Which one was the Most Selling Product by Quantity and by Revenue?
  
3. Which City had maximum revenue, and Which Manager earned maximum revenue?
  
4. What was the Average Revenue?
 
5. What was the Average Revenue of November & December?
  
6. What was the Standard Deviation of Revenue and Quantity?
    
7. What was the Variance of Revenue and Quantity?
 
8. Was the revenue increasing or decreasing over the time?
 
9. What was the Average 'Quantity Sold' & 'Average Revenue' for each product?
 
10. What was the total number of orders or sales made? 

### Tools
-Excel[website](http://office.com)

-Jupyter Notebook

# Cleaning and Preprocessing the Dataset

To ensure data integrity:

1.Importing Libraries & Load Dataset

2.Checking for missing values

3.Removing duplicates (if any)

4.Removing unwanted characters from numeric columns and convert to numbers

### Data Analysis

Code used:
import pandas as pd 
dataset = pd.read_excel("python_SalesData.xlsx")
![image alt]
