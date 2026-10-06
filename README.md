# Superstore Sales Analysis – Excel

## Project Overview

This project analyzes the Superstore sales dataset using Microsoft Excel to identify sales trends, top-performing regions, product categories, customer segments, shipping modes, and products.

The project focuses on data cleaning, exploratory analysis, PivotTables, data visualization, and dashboard development.

## Dataset

The dataset was obtained from **Kaggle**.

* **Rows:** 9,800
* **Columns:** 18
* **Source:** Kaggle Superstore Sales Dataset

The original dataset contains information about orders, customers, products, sales, shipping modes, regions, and dates.

## Tools & Skills

* Microsoft Excel
* Data Cleaning
* Data Validation
* Excel Formulas
* PivotTables
* PivotCharts
* Data Visualization
* Dashboard Design
* Business Insights

## Data Cleaning

Several data-quality checks were performed before analysis:

* Checked the dataset structure and column types.
* Identified **11 missing Postal Code values**.
* Cleaned the `Order Date` column because dates were stored using mixed formats/types.
* Created a helper date column, `OrderDateS`, to convert all order dates into valid Excel dates.
* Verified that all **9,800 order rows** contained usable dates.

The original dataset was preserved, while the cleaned date values were handled using a separate helper column.

## Analysis

The following analyses were created using PivotTables:

1. Sales by Region
2. Sales by Category
3. Sales by Segment
4. Sales by Sub-Category
5. Monthly Sales Trend
6. Sales by Ship Mode
7. Sales by State
8. Top 5 Products by Sales

## Dashboard

The final Excel dashboard includes:

* Total Sales
* Total Orders
* Average Sales per Row
* Highest Sale
* Sales by Region
* Sales by Category
* Monthly Sales Trend
* Sales by Ship Mode
* Top 5 Products by Sales
* Key Business Insights

## Key Insights

* **West generated the highest sales, while South recorded the lowest sales.**
* **Technology was the top-performing category with the highest total sales.**
* **Sales increased significantly in 2017 and 2018, with both years exceeding 2015 sales.**
* **Standard Class generated the highest sales among all shipping modes, while Same Day had the lowest sales.**
* **California and New York together accounted for approximately 33.28% of total sales.**

## Key Findings

### Regional Performance

West was the highest-performing region, while South recorded the lowest sales, indicating a noticeable gap in regional performance.

### Category Performance

Technology generated the highest sales among the three categories, outperforming Furniture and Office Supplies.

### Sales Trend

Sales showed strong growth in 2017 and 2018 compared with the earlier years in the dataset.

### Shipping Mode

Standard Class generated the largest share of sales, while Same Day generated the lowest sales.

### Top States

California and New York were the two highest-performing states and together contributed approximately **33.28% of total sales**.

## Project Structure

Superstore-Sales-Analysis-Excel/
│
├── Superstore_Sales_Analysis_Final.xlsx
└── README.md


The analysis provides a clear view of regional performance, category performance, sales trends, shipping modes, and top-performing products.
