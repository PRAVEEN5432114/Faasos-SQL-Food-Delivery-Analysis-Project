# Faasos 🍽️ SQL Food Delivery Analysis Project

This project is a deep-dive SQL analysis on Faasos food delivery data using structured queries. It explores patterns in customer orders, delivery performance, recipe composition, cancellations, and more.

## 🗃️ Dataset Overview

The project includes the following tables:

- `driver` – Driver details and registration dates
- `ingredients` – Ingredients used in various rolls
- `rolls` – Types of rolls (Veg/Non-Veg)
- `rolls_recipes` – Mapping of rolls to ingredients
- `driver_order` – Delivery details including time, distance, and cancellations
- `customer_orders` – Customer-specific order details

## 🧠 Analysis Performed

- Total rolls ordered
- Unique customer orders
- Successful deliveries by each driver
- Delivered counts by roll type (Veg/Non-Veg)
- Customer-wise roll preference breakdown
- Largest single order by roll count
- Cancellation impact on delivery metrics

## 🛠️ Tools & Skills Used

- SQL Server (compatible syntax)
- Aggregate functions (`COUNT`, `DISTINCT`)
- Window functions (`RANK() OVER`)
- `CASE` statements
- `INNER JOIN`, subqueries

## 📊 Key Insights

- Identified patterns of roll preferences among customers
- Measured driver performance through successful delivery counts
- Highlighted the maximum roll delivery per single order
- Analyzed the effect of cancellations on order completion

## 📁 How to Use

1. Clone the repository
2. Import the SQL script into your SQL Server environment
3. Execute the queries to generate insights

## 🔗 Author

This project was created by D Praveen kumar. Feel free to explore, fork, or contribute!

