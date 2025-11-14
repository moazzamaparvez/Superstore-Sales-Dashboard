Superstore Sales Data Analytics
Overview

This project focuses on exploring and understanding the Superstore sales dataset using Excel. The goal was to take raw sales data, clean it, organize it, and build a clear set of visual insights through PivotTables and an interactive dashboard. The analysis highlights patterns in sales, profit, customer behavior, product performance, and regional trends. This project is part of my Data Analytics portfolio and reflects my ability to work through a complete data workflow from cleaning to reporting.

Tools Used
Microsoft Excel – Data cleaning, PivotTables, charts, slicers, dashboard layout
Power Query – Initial data loading, trimming, text cleaning, and removing duplicate rows

Dataset
Source: Kaggle – Superstore Dataset
Original format: CSV
Cleaned and saved as: sales_data_clean.xlsx

The dataset includes information on orders, customers, regions, profit, sales, and shipping details.

Data Cleaning & Preparation
I spent time preparing the dataset to make sure it was ready for analysis. These were the main steps:
1. Cleaning Text Columns
Text fields often had extra spaces or slight inconsistencies. I cleaned:
Customer Name
Product Name
Category
Customer ID
ZIP Code
Using TRIM, Clean, and Find & Replace helped standardize these columns. Duplicate rows were also removed.

2. Cleaning Numeric Columns
To make calculations accurate and charts clear:
Sales → formatted to 2 decimal places
Profit → formatted to 2 decimals (left negative values because they represent loss)
Quantity → changed to whole numbers
Discount → formatted consistently
This step ensures that PivotTables perform calculations correctly.

4. Cleaning Date Columns
Reformatted Order Date and Ship Date into proper Date format
Created an additional Order Month column for monthly trend analysis
Used the formula: =TEXT([@[Order Date]], "mmm")
This made it easier to build time-based charts.

4. Validations & Final Checks
Before analysis, I verified:
No missing or broken values in key columns
Consistent category names
No invalid ZIP codes
All numeric fields compute correctly in PivotTables
After cleaning, the final dataset looked organized and analysis-ready.

What This Project Shows
This project demonstrates:
The ability to clean and organize a messy real-world dataset
The use of Excel for structured analysis
Understanding of KPIs like sales, profit, customer contribution, and category performance
Skills in building a clear and interactive dashboard with slicers
Turning raw data into meaningful business insights
