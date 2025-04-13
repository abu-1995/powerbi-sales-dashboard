# 📊 Power BI Sales Performance Dashboard

This is a Power BI project built using a MySQL-based sales dataset. The goal of the dashboard is to analyze and visualize sales performance using various metrics and filters.

---

## 🚀 Key Features

- ✅ Total Sales, Quantity, Customer Count KPIs
- ✅ Sales Trend by Month and Year
- ✅ Sales breakdown by:
  - Customer Type (E-Commerce, Brick & Mortar)
  - Product Type (Own Brand, Distribution)
  - Market Zone (North, West, etc.)
- ✅ Dynamic slicers for Year, Month, Product, Customer, and Market


## 🛠️ Tools & Technologies Used

- Power BI (Data model, DAX, Visuals)
- Power Query (Data cleaning & transformation)
- MySQL (Relational Database Source)

---

## 🧹 Data Cleaning Highlight

Using **Power Query**, I cleaned inconsistent and duplicate data from the `currency` column.  
For example:

| Before Cleaning       | After Cleaning |
|-----------------------|----------------|
| `'USD\r'`             | `USD`          |
| `'INR\r'`             | `INR`          |
| `'USD'`               | `USD`          |
| `'INR'`               | `INR`          |

This ensured accurate groupings and correct totals in all currency-based visuals.

---

## 📁 Files Included

- `Project1.pbix` – Complete Power BI report
- `db_dump.sql` – Sample sales database schema (MySQL)
---

## 👨‍💻 How to Use

1. Open `Project1.pbix` in Power BI Desktop
2. Connect to your own MySQL data if needed
3. Explore the dashboard and visuals

---

## 🔗 Connect

Feel free to connect with me on [LinkedIn](#) or explore more on [GitHub](#)!

---
