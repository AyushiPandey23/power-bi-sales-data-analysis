
# Sales Data Analysis

## Problem Statement

This dashboard helps in analyzing sales performance and business insights from the dataset.  
It provides understanding of sales trends over time, product performance, and the relationship between sales and profit.  

The dashboard also enables comparison between two different time periods, helping in identifying growth or decline in performance.  
Additionally, it analyzes the impact of discounts and promotions on sales and highlights top and bottom performing products.  

These insights help businesses make better decisions regarding sales strategy and performance improvement.


### Steps followed 

- Step 1 : Load data into Power BI Desktop.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Performed Data cleaning and transformation using Power Query Editor.
- Step 5 : Added Slicers for Date, Product, Customer Name and Promotion Category.
- Step 9 : Added card visual to display total number of orders.
- Step 10 : Created various charts such as bar chart , line chart, scatter chart and map chart.
- Step 11 : Created multiple report pages for detailed analysis:

             1. Overview Page with sales trends, city-wise sales, and discount analysis.
             2. Product Analysis Page showing top and bottom 5 products.
             3. Time Comparison Page using DAX functions (CALCULATE, ALL, USERELATIONSHIP).
             4. Time Comparison using Edit Interactions.
             5. Detailed data table with multiple filters.

- Step 11 : Created calculated measures for Sales, Profit, and Quantity using DAX.
- Step 12 : Created two date tables using CALENDAR AUTO function for dynamic filtering.
- Step 13 : Used CALCULATE, ALL, and USERELATIONSHIP functions for time-based comparison.


# Insights

### [1] Product Performance

Top 5 and Bottom 5 products were identified based on Sales, Profit, and Quantity Sold.  
This helps in understanding which products are performing well and which need improvement.


### [2] Sales Trends

Sales trends were analyzed over different time periods (daily, monthly, yearly).  
This helps in identifying patterns and seasonal trends in sales.


### [3] Sales vs Profit Relationship

A scatter chart was used to analyze the relationship between sales and profit.  
This helps in identifying high revenue but low profit products.


### [4] Time Period Comparison

Two different time periods were compared using slicers and DAX functions.  
This helps in analyzing business growth and performance changes.



### [5] Discount Analysis

Average discount was analyzed across promotion categories.  
This helps in understanding the impact of discounts on sales.



### [6] City-wise Sales

Sales distribution across different cities was visualized using a map chart.  
This helps identify high-performing regions.


# Snapshots of Report

## Model view
<img width="1907" height="975" alt="Model View" src="https://github.com/user-attachments/assets/5939651e-3759-4e7b-9a7e-ae31a052f06c" />

## Overview Page
<img width="1859" height="993" alt="Overview" src="https://github.com/user-attachments/assets/1bdd783d-e7e8-4893-806a-39581ef0d050" />

## Product Analysis Page
<img width="1914" height="996" alt="Product Analysis" src="https://github.com/user-attachments/assets/142b152f-a4bd-41ef-85d5-b50d3838d921" />

## Comparison Page

### Using DAX
<img width="1913" height="985" alt="Comparison  DAX" src="https://github.com/user-attachments/assets/2aa606fa-b23b-49f2-bd97-bf695e6430eb" />

### Edit Interactions
<img width="1901" height="982" alt="Edit_Interactions" src="https://github.com/user-attachments/assets/59a95ea3-d4d4-4a1e-a1e2-7a0c6de6d085" />

## Table Visual 
<img width="1914" height="991" alt="Table Visual" src="https://github.com/user-attachments/assets/9ee5d3f3-ef11-470c-9a92-deb8de471c94" />



