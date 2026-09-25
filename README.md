🍕 Pizza Sales Analysis Using Power BI

📌 Project Overview

This project focuses on analyzing pizza sales data using "Microsoft Power BI" to understand overall sales performance, ordering trends, pizza category performance, pizza size preferences, and individual pizza performance.

An interactive Power BI dashboard was developed using "Power Query, DAX, and data visualization techniques" to transform raw sales data into meaningful business insights.

---------------------------------

🎯 Project Objectives

The main objectives of this project are to:

* Analyze overall pizza sales performance.
* Track key sales and order KPIs.
* Identify daily and monthly ordering trends.
* Analyze sales performance across pizza categories.
* Understand sales contribution by pizza size.
* Identify the top-performing and bottom-performing pizzas.
* Build an interactive dashboard for business analysis.

---------------------------------

🗂️ Dataset

The dataset contains "48,620 pizza sales records" and provides information about orders, pizzas, prices, quantities, categories, sizes, and ingredients.

 Dataset Columns

| Column              | Description                          |
| ------------------- | ------------------------------------ |
| order_id            | Unique identifier for each order     |
| order_date          | Date on which the order was placed   |
| order_time          | Time at which the order was placed   |
| quantity            | Number of pizzas ordered             |
| pizza_size          | Size of the pizza                    |
| pizza_category      | Category of the pizza                |
| pizza_name          | Name of the pizza                    |
| unit_price          | Price of one pizza                   |
| total_price         | Total price for the ordered quantity |
| pizza_ingredients   | Ingredients used in the pizza        |

----------------------------------------

 🛠️ Tools & Technologies

* "Microsoft Power BI"
* "Power Query"
* "DAX"
* "CSV / Excel"
* "Data Cleaning & Transformation"
* "Data Analysis"
* "Data Visualization"

----------------------------------------

 📊 Key Performance Indicators

The dashboard includes the following key performance indicators:

| KPI                          |       Value |
| ---------------------------- | ----------: |
| **Total Revenue**            | $817,860.05 |
| **Total Orders**             |      21,350 |
| **Total Pizzas Sold**        |      49,574 |
| **Average Order Value**      |      $38.31 |
| **Average Pizzas per Order** |        2.32 |

These KPIs provide a high-level overview of the overall sales performance.

-----------------------------------------

 📈 Power BI Dashboard

The Power BI report contains two main dashboard pages.

1. Main Sales Dashboard

The main dashboard provides an overview of pizza sales performance through:

* Total Revenue
* Total Orders
* Total Pizzas Sold
* Average Order Value
* Average Pizzas per Order
* Daily Total Orders
* Monthly Total Orders
* Sales Percentage by Pizza Category
* Sales Percentage by Pizza Size
* Total Pizzas Sold by Category
* Date slicer
* Pizza Category slicer

These visuals allow users to explore sales performance across different time periods, pizza categories, and sizes.

2. Best & Worst Sellers Dashboard

The second dashboard focuses on individual pizza performance.

It includes:

* Top 5 Pizzas by Revenue
* Bottom 5 Pizzas by Revenue
* Top 5 Pizzas by Quantity Sold
* Bottom 5 Pizzas by Quantity Sold
* Top 5 Pizzas by Number of Orders
* Bottom 5 Pizzas by Number of Orders

This page allows users to compare pizza products using multiple performance metrics.

---------------------------------------
📊 Dashboard Preview

Main Sales Dashboard

![Main Sales Dashboard](main_dashboard.png)

Best & Worst Sellers Dashboard

![Best & Worst Sellers Dashboard](best_worst_sellers.png)
🧮 DAX Measures

DAX measures were created to calculate important business KPIs dynamically.

The main measures include:

"text
Total Revenue
Total Orders
Total Pizzas Sold
Average Order Value
Average Pizzas Per Order
"

These measures respond dynamically to dashboard filters and slicers.

----------------------------------------

🔄 Data Preparation

The data was prepared using **Power Query** before building the dashboard.

The data preparation process included:

* Importing the sales dataset.
* Reviewing column data types.
* Cleaning and transforming the data.
* Preparing date and sales-related fields.
* Creating the required calculations and measures.
* Loading the prepared data into the Power BI data model.

------------------------------------------

🔍 Analysis Performed

 Sales Performance Analysis

Analyzed revenue, order volume, and total pizza quantity sold to understand overall sales performance.

Time-Based Analysis

Analyzed daily and monthly order trends to understand how ordering activity changes over time.

Category Analysis

Compared pizza categories based on their contribution to sales and quantity sold.

Size Analysis

Analyzed sales distribution across different pizza sizes.

Product Performance Analysis

Compared individual pizzas based on:

* Revenue
* Quantity Sold
* Number of Orders

The analysis helps identify products with different levels of sales performance.

-------------------------------------

📁 Project Structure

"text
Pizza-Sales-PowerBI-Analysis/
│
├── README.md
│
├── Dataset/
│   └── pizza_sales.csv
│
├── PowerBI/
│   └── Pizza_Sales_PowerBI_Analysis.pbix
│
└── Dashboard/
    └── dashboard.png
"

---------------------------------------

🚀 How to Use This Project

1. Download the Power BI ".pbix" file from the "PowerBI" folder.
2. Open the file using "Microsoft Power BI Desktop".
3. Explore the dashboard pages.
4. Use the available slicers to filter the analysis.
5. Interact with the visualizations to explore sales trends, categories, sizes, and pizza performance.

----------------------------------------

 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Data Cleaning
* Power Query
* DAX
* KPI Development
* Data Visualization
* Business Intelligence
* Sales Analysis
* Interactive Dashboard Development
* Business Insights

-----------------------------------------

👩‍💻 Author

"Nikhitha Bikkineni"

Computer Science and Engineering Graduate | Aspiring Data Analyst

"Skills:"
Python, SQL, Power BI, Excel, DAX, Data Analysis

------------------------------------------

⭐ Thank you for exploring this project!
