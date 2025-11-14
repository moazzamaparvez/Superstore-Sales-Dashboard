Superstore Sales Data Analytics
Overview

This project showcases my ability to analyze, clean, and visualize real-world sales data using Microsoft Excel. Using the popular Superstore dataset, I transformed raw CSV data into meaningful insights through data cleaning, PivotTables, charts, and an interactive dashboard.

The analysis highlights key trends in regional sales, category performance, monthly profit patterns, and top-performing customers. This project reflects my end-to-end data analytics workflow from data preparation to insight generation.

Tools Used

Microsoft Excel

PivotTables

Charts

Slicers

Dashboard layout

Power Query

Data loading

TRIM & CLEAN transformations

Duplicate removal

Dataset

Source: Kaggle Superstore Dataset

Original Format: CSV

Final Cleaned File: sales_data_clean.xlsx

The dataset includes detailed information on orders, customers, products, regions, shipping, sales, profit, and discounts.

Data Cleaning & Preparation
1. Cleaning Text Columns

Text fields often contained extra spaces or inconsistent formatting. I standardized:

Customer Name

Product Name

Category

Customer ID

ZIP Code

Using Power Query and Excel functions such as TRIM, CLEAN, and Find & Replace, all text values were cleaned. Duplicate rows were also removed to ensure data accuracy.

2. Cleaning Numeric Columns

To ensure accuracy and make calculations consistent across PivotTables:

Sales → formatted to 2 decimal places

Profit → formatted to 2 decimal places (negative profit values kept as they represent loss)

Quantity → converted to whole numbers

Discount → standardized to 2 decimal places

This formatting helped maintain clarity and precision throughout the analysis.

3. Cleaning Date Columns

Reformatted Order Date and Ship Date using a consistent Date format

Added a new Order Month column using:
=TEXT([@[Order Date]], "mmm")

This allowed for clear time-based analysis, such as monthly profit trends.

4. Final Validation

Before building PivotTables and dashboards, I verified that:

No missing or inconsistent values remained

Category names were uniform

All ZIP codes followed a valid format

Numeric fields behaved correctly during calculations

The dataset was then finalized and saved as sales_data_clean.xlsx, ready for analysis.

What This Project Demonstrates

This project highlights my capability to:

Clean and prepare a real-world dataset

Build PivotTable-based analysis efficiently

Create a professional, interactive Excel dashboard

Use slicers to make visuals dynamic and user-friendly

Identify and communicate meaningful business insights

Analyze performance across customers, product categories, time periods, and regions
