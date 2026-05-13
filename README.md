# Sales Performance Analysis Dashboard

## Overview

This project is a **Sales Performance Analysis Dashboard** created using **Power BI** to analyze sales, profit, quantity, discounts, and regional performance.
The dashboard helps businesses track key sales metrics and identify high-performing products and regions through interactive visualizations.

## Features

* Total Orders KPI
* Total Quantity KPI
* Total Sales KPI
* Average Profit KPI
* Region-wise Profit Analysis
* Product Category Profit Analysis
* Product Discount Comparison
* Product Quantity Distribution
* Interactive Filters for:

  * Region
  * Product Category

## Tools & Technologies Used

* Power BI
* MySQL Workbench
* SQL
* Data Visualization
* Data Cleaning & Transformation

## Dataset Information

* Orders
* Products
* Customers
* Stores
* Staffs
* Order Items

### Important Fields

* Order ID
* Product Category
* Region
* Sales
* Quantity
* Profit
* Discount

## KPI Calculations

### Total Sales
Total Sales = SUM(order_items[total_sales])


### Total Orders
Total Orders = COUNT(orders[order_id])


### Total Quantity
Total Quantity = SUM(order_items[quantity])


### Average Profit
Average Profit = AVERAGE(order_items[profit])

## Dashboard Visualizations

| Visualization          | Purpose                            |
| ---------------------- | ---------------------------------- |
| KPI Cards              | Display important business metrics |
| Bar Chart              | Region-wise profit comparison      |
| Line Chart             | Profit by product category         |
| Pie Chart              | Average profit distribution        |
| Clustered Column Chart | Product discount analysis          |
| Horizontal Bar Chart   | Quantity analysis                  |

## Key Insights

* East region recorded the highest quantity count.
* Clothing category generated strong profits.
* Product discounts vary across categories and regions.
* Interactive filters improve detailed analysis.

## Learning Outcomes

* Power BI Dashboard Design
* Data Modeling
* DAX Calculations
* SQL Database Connection
* Business Data Analysis
* Interactive Reporting

## Author

**Ramya Ravichandran**
