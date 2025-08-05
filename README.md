# 🍕 Pizza Sales SQL Project

This project analyzes a pizza sales dataset using **MySQL** to extract business insights through SQL queries.

---

## 📌 Objective

- Analyze pizza sales performance
- Identify top-selling pizzas and categories
- Track sales trends by date, size, and type
- Support decision-making with data
---
## 🧰 Tools Used

- **MySQL** – Querying and data analysis

## 📁 Project Files

| File Name                  | Description                            |
|---------------------------|----------------------------------------|
| `pizza_sales_analysis.sql`| Contains all SQL queries used for analysis |

---

## 🔍 Sample SQL Query

```sql
SELECT pizza_category, SUM(total_price) AS total_revenue
FROM pizza_sales
GROUP BY pizza_category
ORDER BY total_revenue DESC;


## 👨‍💻 Author

**Gaurav Diwate**  
🔗 [GitHub Profile](https://github.com/Gauravdiwate)

