# ☕ Starbucks Daily Sales Analysis Dashboard — Power BI Project

An interactive Power BI dashboard built to analyze Starbucks daily sales performance — covering revenue trends, customer behavior, order patterns, and hourly sales breakdowns.

## 📌 Project Overview

This project transforms raw transactional data into a clean, interactive dashboard that helps track:
- Daily sales performance
- Customer buying patterns
- Hourly order and revenue trends
- Product-level sales details

The dashboard was built entirely in **Power BI Desktop**, using DAX measures and custom visuals for a clean, business-ready look.

## 🎯 Objective

To help stakeholders quickly answer:
- What is the total revenue and order volume for the day?
- How many unique customers are placing orders?
- Which hours of the day drive the most sales?
- What is the average order value across transactions?

## 🗂️ Dataset

Three CSV files were used to build this project (found in the `/data` folder):

| File | Description |
|------|--------------|
| `customers.csv` | Customer details — ID, name, email, phone, age, gender |
| `items.csv` | Product catalog — item name, calories, fat, carbs, fiber, protein, category |
| `sales.csv` | Transaction records — transaction ID, store, datetime, customer, item, quantity, price, total amount, payment mode |

These three tables were connected using relationships in Power BI's data model (customer_id and item_id as keys) to build a unified sales analysis.

## 📊 Dashboard Features

**Page 1 — Overview KPIs**
- Order Count
- Total Amount
- Customer Count
- Total Quantity

**Page 2 — Hourly Trends**
- Average Order Amount by Hour
- Total Sales Amount by Hour
- Total Quantity Sold by Hour

**Page 3 — Transaction Detail Table**
- Customer name, item purchased, transaction ID, payment mode, customer type
- Broken down by Year, Quarter, Month, and Day
- Aggregated totals for Amount, Quantity, Average Order Amount, and Order Count

## 🛠️ Tools & Technologies

- **Power BI Desktop** — dashboard design and DAX measures
- **Power Query** — data cleaning and transformation
- **CSV** — raw data source

## 📂 Project Structure

```
starbucks-sales-dashboard/
│
├── README.md
├── dashboard/
│   └── Starbucks_Sales_Dashboard.pbix
├── data/
│   ├── customers.csv
│   ├── items.csv
│   └── sales.csv
├── screenshots/
│   ├── dashboard-overview.png
│   └── dashboard-table.png
└── demo/
    └── screen-recording link (see below)
```

## 🎥 Demo Video

A full screen recording walkthrough of the dashboard is available here:
👉 https://github.com/NIVETHITHA217/starbucks-sales-dashboard/blob/main/Screen%20Recording%202026-09-09%20204512.mp4

## 🚀 How to Use

1. Download or clone this repository.
2. Open `dashboard/Starbucks_Sales_Dashboard.pbix` in **Power BI Desktop**.
3. If prompted, refresh the data connections and point them to the CSV files in the `/data` folder.
4. Explore the interactive visuals and filters.

## 📈 Key Insights

- Peak sales hours were observed around midday and early evening.
- A small set of regular customers contributed to repeat orders across multiple days.
- UPI and Card were the most frequently used payment modes.

## 👤 Author

**[Your Name]**
📧 nivepakkiri@gmail.com
🔗 https://www.linkedin.com/in/nivethitha-pakkiri/

---
⭐ If you found this project useful, consider giving it a star!
