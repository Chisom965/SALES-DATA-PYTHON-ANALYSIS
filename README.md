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

![image alt](https://github.com/Chisom965/SALES-DATA-PYTHON-ANALYSIS/blob/aeea86a3662a57715b4c6727b5cd43583eea68fb/py%201.png)

dataset["Date"] = pd.to_datetime(dataset["Date"], errors="coerce") 
dataset["Price"] = pd.to_numeric(dataset["Price"], errors="coerce") 
dataset["Quantity"] = pd.to_numeric(dataset["Quantity"], errors="coerce")

[![image alt]](https://github.com/Chisom965/SALES-DATA-PYTHON-ANALYSIS/blob/9910ea9b2212de88c5569c1779843ac8d4edb148/py%203.png)

### Insights
-Credit Card payments dominate sales transactions.

- Beverages are most sold by quantity, while Burgers generate the most revenue
  
 - Lisbon city and Manager Joao Silva outperform others in revenue contribution.

 - Revenue steadily increases, with a strong peak in November & December (holiday effect).
   
### RECOMMENDATIONS 

1. Expand credit card payment support to improve customer convenience.
   
2. Promote Burgers more aggressively since it yields higher revenue.
    
3. Replicate strategies used in Lisbon to boost other cities.
     
4. Reward and support high-performing managers like Joao Silva.

## Results

[![image alt](https://github.com/Chisom965/SALES-DATA-PYTHON-ANALYSIS/blob/c50faafa1f118d26a439377a1c16a5076a982199/CHISOM%20FAITH%20CHIJIOKE%20SALES%20DATA%20PYTHON%20ANALYSIS%20PROJECT%20REPORT.pdf)

   
