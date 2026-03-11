# Sales Analysis (Excel + Power Pivot)



This project analyzes sales data from FNP (Fern & Petals) using Microsoft Excel, Power Query, and Power Pivot to create a fully interactive business dashboard for analyzing revenue performance, customer demand, and product trend

# Problem Statement
You have been given a dataset from FNP (Ferns and Petals) that specializes in sending gifts for various occasions like Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries. The dataset contains details about the products, orders, customers, and relevant dates. Your task is to analyze this dataset to uncover key insights related to sales trends, customer behavior, and product performance.
# Tools & Skills Used
Tools Used  <br>
•	Microsoft Excel <br>
•	Power Query (ETL – Extract, Transform, Load) <br>
•	Power Pivot (Data Modeling & DAX) <br>
•	Pivot Tables & Pivot Charts <br>
•	Excel Formulas & DAX Functions <br>
•	Interactive Slicers <br>

# Dataset Description
The analysis uses three relational datasets: <br>
•	Orders Table <br>
•	Customers Table <br>
•	Products Table <br>
These datasets were connected using Power Pivot relationships to enable cross-table analysis. <br>

# Data Preparation
Data Cleaning & Transformation (Power Query) <br>
Used Power Query to prepare the dataset by: <br>
•	Removing unnecessary columns <br>
•	Standardizing data types <br>
•	Cleaning raw order data <br>
•	Creating calculated columns (Month, Revenue, Order metrics) <br>

Data Modeling (Power Pivot) <br>
Built a relational data model between: <br>
•	Orders <br>
•	Customers <br>
•	Products <br>
This enabled multi-table analysis using Pivot Tables and DAX. <br>
📊 DAX Calculations <br>
Created calculated columns in Power Pivot for deeper analysis. <br>
Example: <br>
Day_Name = FORMAT('Order'[Order_Date], "DDDD") <br>
Used to analyze sales trends by day of the week. <br>
# Dashboard Features 
 Dashboard KPIs <br>
The dashboard highlights key performance metrics: <br>
•	Total Revenue: ₹35,20,984 <br>
•	Average Revenue per Order: ₹3,520 <br>
•	Average Delivery Time: 5.53 days <br>
•	Total Orders: 1000 <br>
 Data Visualizations <br>
The dashboard includes the following analytical views: <br>
Revenue Analysis <br>
•	Revenue by Month <br>
•	Revenue by Occasion <br>
Geographic Analysis <br>
•	Top 10 Cities by Orders  <br>
Product Performance  <br>
•	Revenue by Category  <br>
•	Top 5 Products by Revenue  <br>
Operational Insights  <br>
•	Sales by Day of Week  <br>
•	Average Delivery Time   <br>

🎛 Interactive Features  <br>
Interactive Slicers allow dynamic filtering by:  <br>
•	Order Date  <br>
•	Delivery Date  <br>
•	Occasion  <br>

# Key Insights 
• Sales peak during February–March and August, indicating strong seasonal demand.  <br>
• Anniversary and Raksha Bandhan generate the highest revenue among occasions.  <br>
• Colors, Soft Toys, and Sweets are the top-performing product categories.  <br>
• A small number of products contribute significantly to overall revenue.  <br>
• Cities like Bareilly and Ghaziabad have higher order volumes.  <br>
• Sales are stronger on Tuesdays and Sundays, suggesting weekday demand variation. <br>

