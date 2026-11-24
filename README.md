# -Multi-Year-Sales-Performance-Analysis
# Multi-Year Sales Performance Analysis (2020–2022)

## 📌 Project Overview
This project analyzes a transactional retail dataset spanning three years (2020–2022) across four regions (**North, South, East, West**) and five product categories (**Art, Computer, Electronics, Mobiles, Storage**) [0.1.1]. The goal is to evaluate revenue trends, seasonal performance, product demand, and profitability [0.1.1].

## 📊 Dataset Summary
* **Total Orders:** 981 [0.1.1]
* **Total Quantity Sold:** 4,279.8 units [0.1.1]
* **Total Revenue:** 9,843,042 [0.1.1]
* **Total Profit (10% Margin):** 984,304.2 [0.1.1]

### Key Fields
`Order id` | `Order Date` | `Year` | `Cust ID` | `Region` | `Cust Name` | `Category` | `Product` | `Price` | `Qty` | `Amount` | `Profit 10%` [0.1.1]

## 🔍 Key Insights

### 1. Category Performance
| Category | Total Revenue | Total Quantity Sold |
| :--- | :---: | :---: |
| **Mobiles** | 2,175,180 | 842.2 |
| **Storage** | 2,016,958 | 888.6 |
| **Electronics** | 1,999,150 | 870.0 |
| **Art** | 1,974,370 | 857.4 |
| **Computer** | 1,677,384 | 821.6 |
 [0.1.1]

### 2. Quarterly & Monthly Trends
* **Strongest Quarter:** Q3 generated the highest revenue at **3,095,380** (~31.4% of total sales), followed by Q1 (**2,414,032**) [0.1.1].
* **Peak Month:** **July** recorded the highest monthly sales (**1,181,320**) and unit volume (**514 units**) [0.1.1].
* **Slowest Month:** **November** saw the lowest activity with 56 orders and **560,120** in revenue [0.1.1].

## 🛠️ Tools & Techniques Used
* **Microsoft Excel:** Pivot Tables for multi-dimensional aggregation (Monthly, Quarterly, and Category breakdowns) [0.1.1].
* **Data Auditing:** Identified anomalies in raw logs, including duplicate `Order id` entries, fractional quantities, and dynamic unit pricing across 2022 records [0.1.1].

## 🚀 Future Improvements
* Perform automated data cleaning using Python (`pandas`) to deduplicate order records and standardize SKU pricing.
* Build an interactive dashboard in Power BI or Tableau to visualize regional performance over time.
