# E-commerce Sales Performance Dashboard (Power BI)

An interactive, dark-themed Power BI business dashboard designed to analyze retail sales, profitability trends, customer payment behavior, and regional distribution.

---

## 📌 Project Overview
This project visualizes core e-commerce business KPIs to provide actionable operational insights into sales performance across product lines, states, and payment channels.

### Key Metrics Tracked
* **Total Sales:** 438K
* **Total Profit:** 37K
* **Total Orders:** 6K
* **Average Order Value (AOV):** 84

---

## 🔍 Key Insights & Findings
* **Regional Dominance:** Maharashtra leads total revenue generation (102K), followed by Madhya Pradesh (87K).
* **Payment Preferences:** Cash on Delivery (COD) accounts for 46% of all orders, with UPI serving as the second most preferred method at 22%.
* **Volume vs. Revenue:** While Clothing leads in order volume, Electronics generates the highest gross revenue.
* **Profit Seasonality:** Identifies seasonal margin dips in May (-3.7K), July (-2.1K), and September (-1.4K), contrasted by strong profitability peaks in November (10.3K).

---

## 🛠️ Features & DAX Measures
* **Dynamic Slicers:** Filter data dynamically by Quarter (Qtr 1–4) and State.
* **Dual-Axis Combo Visual:** Simultaneously analyzes order volume trends against gross sales across categories.
* **Calculated Metrics:** 
  * `Total Sales = SUM(Sales[Amount])`
  * `Total Profit = SUM(Sales[Profit])`
  * `Average Order Value = DIVIDE(SUM(Sales[Amount]), AVG(Sales[Quantity]))`

---

## 📂 Repository Contents
* `Ecommerce_Sales_Dashboard.pbix` — Full interactive Power BI report file.
* `dataset/` — Raw dataset file (CSV/Excel).
* `preview.png` — Dashboard screenshot preview.

---

## 🚀 How to View
1. Clone this repository or download `Ecommerce_Sales_Dashboard.pbix`.
2. Open the file in **Power BI Desktop**.
3. Interact with the slicers to filter performance dynamically.
