# 🍕 Pizza Hut Sales Analysis using SQL

## 📌 Project Overview
This project focuses on **analyzing Pizza Hut sales data using SQL** to derive meaningful, data-driven insights related to **customer behavior, sales performance, and revenue contribution**.  
The analysis demonstrates how raw transactional data can be transformed into **actionable business intelligence** using SQL queries.

## 🏢 Business Context
In today’s data-driven environment, food and beverage companies generate large volumes of transactional data.  
Pizza Hut, as a leading global pizza chain, collects data related to orders, pizza types, prices, and customer demand.  
Without proper analysis, this data remains underutilized.

This project bridges the gap between **raw data and strategic decision-making** by applying SQL to uncover trends, patterns, and insights that support business growth and operational efficiency.

## ❓ Problem Statement
The main problem addressed in this project is transforming **raw Pizza Hut sales data** into meaningful insights to:

- Identify top-selling pizzas and categories  
- Understand customer ordering patterns  
- Analyze revenue contribution by pizza type and size  
- Determine peak order times  
- Support inventory, staffing, and marketing decisions  

## 🎯 Project Objectives
- Explore and clean the Pizza Hut sales dataset  
- Identify the most frequently ordered pizzas  
- Analyze sales distribution by category, size, and price  
- Determine peak order hours and high-demand periods  
- Evaluate revenue contribution by pizza type and category  
- Apply **basic, intermediate, and advanced SQL queries**  
- Strengthen practical SQL and analytical skills  

## 📂 Dataset Description
The analysis is based on **four relational CSV files**:

### 1. `pizzas.csv`
- `pizza_id` – Unique identifier for pizza variants  
- `pizza_type_id` – Links to pizza types  
- `size` – Pizza size (S, M, L, XL)  
- `price` – Price of the pizza  

### 2. `pizza_types.csv`
- `pizza_type_id` – Unique identifier  
- `name` – Pizza name  
- `category` – Veggie, Chicken, Classic, Supreme  
- `ingredients` – Ingredients list  

### 3. `orders.csv`
- `order_id` – Unique order identifier  
- `date` – Order date  
- `time` – Order time  

### 4. `order_details.csv`
- `order_details_id` – Unique order detail ID  
- `order_id` – Links to orders  
- `pizza_id` – Ordered pizza  
- `quantity` – Quantity ordered  

These tables form a **relational database**, ideal for SQL-based analysis.

## 🧠 Analysis Approach
The project is structured into **three levels of SQL analysis**:

### 🔹 Basic Analysis
- Total number of orders  
- Total revenue generated  
- Highest-priced pizza  
- Most frequently ordered pizza size  
- Top 5 pizzas by order quantity  

### 🔹 Intermediate Analysis
- Quantity ordered by pizza category  
- Order distribution by hour of the day  
- Category-wise order analysis  
- Average daily pizza orders  
- Top 3 pizzas by revenue  

### 🔹 Advanced Analysis
- Revenue contribution (%) by pizza type  
- Cumulative revenue growth over time  
- Top 3 revenue-generating pizzas within each category  

## 🔍 Key Insights
- A small number of pizzas contribute a large share of total revenue (Pareto principle)  
- Medium and large pizzas are the most preferred sizes  
- Peak order times occur during **lunch (12–2 PM)** and **dinner (6–9 PM)**  
- Classic and Supreme categories show strong customer demand  
- Revenue demonstrates steady cumulative growth over time  

## 💡 Business Recommendations
- Focus marketing efforts on top revenue-generating pizzas  
- Maintain sufficient inventory for high-demand categories  
- Introduce combo offers for premium pizzas  
- Optimize staff scheduling based on peak order hours  
- Review and remove low-performing pizzas to improve efficiency  

## 🛠 Tools & Technologies
- SQL (Joins, Aggregations, Subqueries, Window Functions)  
- MySQL / SQL-based RDBMS  
- CSV Datasets

  
## ✅ Conclusion
1.This project highlights the *practical application of SQL* in analyzing real-world sales data.  
2.By transforming raw transactional data into meaningful insights, the analysis supports *better business decisions, improved operational efficiency, and enhanced customer satisfaction*.


  

---

## 📁 Project Structure
