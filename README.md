🍕 Pizza Sales SQL Project – Summary

This SQL project is designed to analyze pizza sales data from the database Pizza DB. The queries are structured into KPIs, trend analysis, category insights, and top/bottom performers.

🔑 Key Performance Indicators (KPIs)

Total Revenue – Calculates the overall revenue (SUM(total_price)).

Average Order Value – Revenue per order (SUM(total_price) / COUNT(DISTINCT order_id)).

Total Pizzas Sold – Number of pizzas sold (SUM(quantity)).

Total Orders – Number of unique orders (COUNT(DISTINCT order_id)).

Average Pizzas per Order – Average number of pizzas per order.

📊 Trend Analysis

Daily Orders Trend – Orders grouped by day of the week.

Monthly Orders Trend – Orders grouped by month.

🍕 Category & Size Analysis

Revenue by Pizza Category – Contribution of each pizza category to total sales.

Revenue by Pizza Size – Contribution of each pizza size to total sales.

Percentage Contribution – Category and size sales expressed as % of total revenue.

🏆 Top & Bottom Performers

Top 5 Best-Selling Pizzas (by Revenue)

Top 5 Best-Selling Pizzas (by Quantity)

Top 5 Best-Selling Pizzas (by Orders)

Bottom 5 Worst-Selling Pizzas (by Revenue, Quantity, and Orders)

✅ Purpose

This SQL file is essentially the backend for a Pizza Sales Dashboard.
It provides:

Business insights on sales, demand, and customer behavior.

Helps identify high-performing products and areas for improvement.

Supports decision-making in pricing, product mix, and marketing.
