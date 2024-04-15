# Sales Analysis with Pandas

## Overview
This repository contains a sales analysis project using Python's pandas library. The project involves merging sales data from multiple CSV files, cleaning the data, performing various analysis tasks, and visualizing the results.

## Dependencies
- pandas
- os
- glob
- matplotlib

## Tasks

### Task 1: Merging 12 Months of Sales Data into a Single File
- Load all CSV files from a directory into a DataFrame.
- Concatenate the DataFrames into a single DataFrame.
- Save the merged DataFrame to a new CSV file.

### Task 2: What was the Best Month for Sales? How Much Was Earned that Month?
- Clean the data by removing rows with missing values.
- Calculate total sales for each month.
- Identify the month with the highest sales and the corresponding earnings.

### Task 3: What City Had the Highest Number of Sales?
- Extract city information from the 'Purchase Address' column.
- Group the data by city and calculate total sales for each city.
- Determine the city with the highest number of sales.

### Task 4: What Time Should We Display Advertisements to Maximize Likelihood of Customers Buying Products?
- Extract hour information from the 'Order Date' column.
- Group the data by hour and count the number of orders placed during each hour.
- Visualize the results to identify peak ordering hours.

### Task 5: What Products Are Most Often Sold Together?
- Identify duplicate orders based on the 'Order ID' column.
- Group the duplicate orders and create a new column with grouped product names.
- Find the most common pairs of products sold together.

### Task 6: What Product Sold the Most? Why Do You Think It Sold the Most?
- Group the data by product and calculate the total quantity ordered for each product.
- Visualize the quantity ordered for each product.
- Analyze the relationship between product price and quantity ordered.

## Conclusion
This project demonstrates the power of pandas for data analysis tasks, including data cleaning, manipulation, analysis, and visualization. By following the tasks outlined above, valuable insights can be gained from sales data, helping businesses make informed decisions and optimize their operations.
