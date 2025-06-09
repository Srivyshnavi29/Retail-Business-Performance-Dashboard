# 🛍️ Retail Business Performance Dashboard – Power BI + Python

This project is a **real-time, end-to-end data analytics solution** for a simulated multi-store retail chain. It leverages Power BI for interactive business intelligence reporting and Python for data cleaning. The dashboard helps stakeholders track store performance, regional insights, and department efficiency to make data-driven business decisions.

---

## 📦 Dataset Overview
- 2 years of weekly sales data (2023–2024)
- 5 stores, 5 departments, and 5 regions
- Includes: Store, Department, Region, Weekly Sales, Transactions

---

## 🧰 Tools Used
- **Python (Pandas)** – Data cleaning and preprocessing
- **Excel** – For storing and transforming structured data
- **Power BI** – For dashboard design and interactive insights

---

## ❓ Stakeholder Questions Answered

| Business Question | Answered in |
|-------------------|-------------|
|  How are total sales trending week over week? | Line Chart (Page 1) |
|  Which store performed best overall? | Column Chart (Page 1) |
|  Which department drives the most revenue? | Bar Chart (Page 2) |
|  Are there seasonal spikes or drops in sales? | Monthly Trend Line (Page 1) |
|  Which region is underperforming? | Region Sales Pie Chart (Page 1) |
|  Which region sells which departments the most? | Matrix (Page 2) |
|  What’s the average revenue per transaction? | KPI Card + Column Chart (Page 2) |
|  Are some stores or departments having low transactions? | Table View (Page 2) |
|  Which stores need urgent attention? | Matrix + Table Analysis |
|  What strategic improvements are recommended? | Text box (Insights Section) |

---

## 📊 Dashboard Features

### 📄 Sheet 1: Executive Summary
- 🧾 Total Sales, Total Transactions, Revenue/Transaction KPIs
- 📈 Weekly and Monthly Sales Trends
- 📍 Sales by Store and Region
- 🎛️ Slicers for Store, Region, Year

![Executive Summary](Sheet1.png)

---

### 📄 Sheet 2: Operational & Departmental Insights
- 📊 Sales by Department
- 🧮 Revenue per Transaction (Store-wise)
- 📉 Low-performing Stores & Departments (Transaction-based)
- 📊 Region x Department Matrix View
- 🎛️ Department and Month Slicers

![Operational Insights](Sheet2.png)

---

## 💡 Business Insights
- **Store_3** had the highest total sales; **Store_5** had the most consistent growth.
- **Groceries** generated the most revenue across all departments.
- **Central and South regions** require improvement in average transaction volumes.
- **Store_2** has the highest revenue per transaction, suggesting higher-value purchases.

---

## 📝 Files in This Repository

| File | Description |
|------|-------------|
| `Retail_Business_Dashboard.pbix` | Main Power BI report |
| `Cleaned_Retail_Data.xlsx` | Dataset used for visualizations |
| `Sheet1.png` | Screenshot of Executive Summary (Page 1) |
| `Sheet2.png` | Screenshot of Operational Insights (Page 2) |
| `README.md` | Project overview and documentation |

---

## 🚀 How to Use
1. Clone or download this repository.
2. Open `Retail_Business_Dashboard.pbix` in **Power BI Desktop**.
3. Explore visuals using slicers and filters.
4. Review insights and trends from both dashboard pages.

---

*This project is part of my personal data analyst portfolio, focused on real-time retail analytics. Feel free to explore or fork it for learning or enhancement!*
