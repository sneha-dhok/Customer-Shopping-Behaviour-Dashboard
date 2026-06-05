# Customer-Shopping-Behaviour-Dashboard
🎯 Goal / Objective
The goal of this project is to analyze customer shopping behavior, purchasing patterns, subscription trends, and category-wise revenue performance using an end-to-end analytics workflow.

This project demonstrates a complete real-world Data Analytics pipeline involving:

Data Cleaning using Python
Data Analysis using SQL
Interactive Dashboard Development using Power BI
The dashboard helps businesses understand customer preferences, optimize sales strategies, and improve customer
🚀 End-to-End Workflow
🔹 Step 1: Data Cleaning & Preprocessing (Python)
Performed data cleaning and preprocessing using:

Pandas
NumPy
Jupyter Notebook
Tasks Performed
✅ Null Value Treatment

✅ Duplicate Removal

✅ Feature Engineering

✅ Connection to MySQL Workbench

🔹 Step 2: Data Analysis (SQL)
Performed SQL-based business analysis to extract insights.

SQL Concepts Used
SELECT Statements
GROUP BY
ORDER BY
Aggregate Functions
CASE WHEN
Subqueries
CTEs
Window Functions
🔹 Step 3: Dashboard Development (Power BI)
Created an interactive Power BI dashboard for business reporting and visualization.

💡 Key Business Insights
📈 Customer Insights
Total Customers Analyzed: 3.9K
Average Purchase Amount: $59.76
Average Review Rating: 3.75

🛒 Sales Insights
Clothing category generated the highest sales
Accessories and Footwear contributed significant revenue
Outerwear showed comparatively lower sales performance

👥 Customer Behavior Insights
73% customers do not have subscriptions
27% customers are subscribed
Adult and Middle-Aged customers generated the highest revenue
Young Adults contributed high purchase frequency

💰 Revenue Insights
Revenue distribution analyzed by:
Product Category
Age Group
Subscription Status
Gender
Shipping Type
🛠 Technologies Used
Category	Tools / Technologies
Programming Language	Python
Python Libraries	Pandas, NumPy, Matplotlib
SQL Database	MySQL
BI Tool	Power BI Desktop
Data Source	CSV Dataset
Query Language	SQL
Data Transformation	Power Query
Calculations	DAX

📊 Dashboard Features
KPI Cards
Number of Customers
Average Purchase Amount
Average Review Rating
Interactive Visuals
📌 Sales by Category
Analyzes sales distribution across:

Clothing
Accessories
Footwear
Outerwear
📌 Revenue by Category
Shows revenue contribution from each category.

📌 Revenue by Age Group
Analyzes customer spending behavior by:

Young Adult
Adult
Middle Aged
Senior
📌 Subscription Analysis
Compares subscribed vs non-subscribed customers.

📌 Dynamic Slicers
Interactive filtering based on:

Gender
Category
Subscription Status
Shipping Type
📈 Key DAX Measures
Total Customers
Number of Customer = COUNT('customer_behavior customer'[customer_id])
Average Purchase Amount
Average Purchase Amount = AVERAGE('customer_behavior customer'[purchase_amount])
Average Review Rating
Average review Rating = AVERAGE('customer_behavior customer'[review_rating])

🧩 Data Model
Fact Table
shopping_data
Important Columns
Customer_ID
Gender
Age
Category
Purchase_Amount
Review_Rating
Subscription_Status
Shipping_Type

🎨 Visuals Used
Visual	Purpose
KPI Cards	Summary Metrics
Bar Charts	Sales Comparison
Column Charts	Revenue Analysis
Pie/Donut Charts	Subscription Analysis
Slicers	Interactive Filtering
🖥 Screenshots

📌 Dashboard Preview
Find Customer_shopping_behavior Dashboard.pdf

🧭 Dashboard Navigation
📍 How to Use Dashboard
🔹 Analyze KPIs
Track:

Customer Count
Purchase Amount
Review Ratings
🔹 Use Filters
Filter dashboard using:

Gender
Category
Subscription Status
Shipping Type

🔹 Analyze Customer Segments
Understand:
Customer Age Groups
Revenue Contribution
Purchase Behavior

📊 Business Impact
This project helps businesses:

Improve customer targeting
Understand shopping behavior
Optimize product strategy
Increase customer retention
Improve sales performance
