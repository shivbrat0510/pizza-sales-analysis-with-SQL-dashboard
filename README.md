# 🍕 Pizza Sales Dashboard -- 1

---

## 📊 Key Metrics
- **Total Revenue:** $817.86K  
- **Total Pizzas Sold:** 49,574  
- **Total Orders:** 21,350  
- **Average Order Value:** $38.31  
- **Average Pizzas per Order:** 2.32  

---

## 📅 Sales Trends
- **Monthly Trends for Total Orders:**  
  - Orders vary across the year, peaking in certain months.  
- **Busiest Days:** Thursday, Friday, Saturday  
- **Busiest Times:** 12 PM – 1 PM, 5 PM – 8 PM  

---

## 🍽 Sales by Category
- **Classic Pizzas** – Highest sales  
- **Supreme Pizzas** – Strong performance  
- **Chicken Pizzas** – Moderate sales  
- **Veggie Pizzas** – Lowest sales  

---

## 📐 Sales by Size
- **Large Pizzas** – Most popular  
- **Medium Pizzas** – Second most sold  
- **Regular Pizzas** – Moderate  
- **XLarge & Small Pizzas** – Minimal contribution  

---

## 📈 Performance Insights
- Classic pizzas dominate both **revenue and volume**.  
- Large pizzas are the preferred size by customers.  
- Sales peak during **weekends** and **lunch/dinner times**.  
- Opportunities exist in promoting **veggie pizzas** and **smaller sizes**.  

---

🍕 Pizza Sales – Best & Worst Sellers Dashboard --2

This dashboard highlights the top and bottom-performing pizzas based on revenue, quantity sold, and total orders.

🔝 Best Sellers

Top Pizza by Revenue: The Thai Chicken Pizza

Top Pizza by Quantity: The Classic Deluxe Pizza

Top Pizza by Total Orders: The Classic Deluxe Pizza

🔝 Top 5 Pizzas (by Metric)

By Revenue: Thai Chicken, Barbecue Chicken, California Chicken, Five Cheese, Italian Supreme

By Quantity: Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, Thai Chicken

By Total Orders: Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, Thai Chicken

🔻 Worst Sellers

Lowest Revenue Pizza: The Brie Carre Pizza

Lowest Quantity Pizza: The Brie Carre Pizza

Lowest Total Orders Pizza: The Brie Carre Pizza

🔻 Bottom 5 Pizzas (by Metric)

By Revenue: Brie Carre, Greek, Spinach Supreme, Green Garden, Mediterranean

By Quantity: Brie Carre, Greek, Spinach Supreme, Green Garden, Mediterranean

By Total Orders: Brie Carre, Greek, Spinach Supreme, Green Garden, Mediterranean

📊 Key Insights

Classic Deluxe and Thai Chicken are the strongest performers across all metrics.

Brie Carre consistently ranks lowest in revenue, quantity, and orders.

Top 5 pizzas significantly outperform bottom 5, suggesting opportunities for menu optimization or targeted promotions for low performers.


















---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
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
