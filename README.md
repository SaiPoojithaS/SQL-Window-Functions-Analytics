# 📊 Sales Performance Insights using SQL Window Functions & Power BI

This project demonstrates the use of **SQL Window Functions** and **DAX** to perform advanced data analysis and storytelling using Power BI.

---

## 🚀 Project Objective

To analyze employee sales performance across regions and months using:
- SQL window functions (`RANK`, `LAG`, `NTILE`, etc.)
- Power BI for dashboard visualization
- DAX to simulate window logic inside Power BI

---

## 📁 Dataset

The dataset (`sales_data_cleaned.csv`) contains:
- `Employee`: Salesperson name
- `Region`: Sales region (North/South)
- `Month`: Monthly sales dates (Jan–Mar 2024)
- `Sales`: Sales amount

---

## 🛠 Tools Used

- 🐍 **Python + SQLite** in Jupyter Notebook
- 📊 **Power BI Desktop**
- 🧠 **SQL** & **DAX** (`RANKX`, `SWITCH`, `CALCULATE`, etc.)

---

## 🔍 Key Insights Extracted

- 🔢 Ranked top salespeople using `RANK()` and `DENSE_RANK()`
- 📉 Tracked sales changes month-over-month with `LAG()`
- 🥧 Simulated NTILE() logic using `RANKX + SWITCH` in Power BI to classify quartiles
- 📋 Created a snapshot summary table showing first & latest sales activity per employee

---

## 📸 Dashboard Preview

*Add a screenshot of your dashboard here, or describe your visuals like this:*

- ✅ **Bar Chart**: Top Employees by Region
- ✅ **Line Chart**: Sales Trends over Time
- ✅ **Pie Chart**: Sales Quartile Breakdown (Top 25%, 50%, etc.)
- ✅ **Table**: Employee sales summary (with `SalesRank` and Quartile)

---

## 📎 Files Included

| File Name | Description |
|-----------|-------------|
| `sales_data_cleaned.csv` | Cleaned mock dataset |
| `Sales_Performance_Insights.pbix` | Power BI Dashboard |
| `Sales_SQL_Window_Functions_Project.ipynb` | SQL window function queries |
| `README.md` | Project documentation |

---

## 👩‍💻 Created By

**Poojitha (Sai Siddaraju Poojitha)**  
🎯 Data Analytics | Visualization | SQL | Power BI

---

📬 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/) or check out more on my [GitHub](https://github.com/your-username)
