# 🛒 Superstore Sales Dashboard 

<img width="749" height="470" alt="dashboard-preview" src="https://github.com/user-attachments/assets/df455547-bffd-41a1-b185-7e69430196cb" />



**An end-to-end interactive business intelligence dashboard built entirely in Microsoft Excel — no Power BI, no Tableau, no code.**

---

## 🚀 Live Demo

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $22,97,200.86 |
| 📈 Total Profit | $2,86,397.02 |
| 📊 Profit Margin | 12.47% |
| ⚠️ Loss Transactions | 18.72% |

---

## 📌 Project Overview

This project transforms **4 years of raw Superstore retail data** into a fully interactive, single-screen executive dashboard using only Microsoft Excel. Every chart, KPI card, and slicer was built from scratch using Pivot Tables, PivotCharts, and advanced Excel features.

**The Goal:** Answer critical business questions at a glance — *Where are we winning? Where are we losing money? Which customers drive the most revenue?*

---

## ✨ Features

- 🎯 **4 Dynamic KPI Cards** — Total Sales, Total Profit, Profit Margin %, Loss Transaction %
- 📉 **Monthly Sales Trend** — Line chart showing seasonality across 2014–2017
- 🌍 **Revenue by Region** — Horizontal bar chart sorted descending
- 🪑 **Profit by Category** — Column chart with Furniture highlighted red (loss-maker)
- 👑 **Top 10 Customers by Revenue** — Ranked horizontal bar chart
- 💸 **How Discounting Destroys Profit** — Clustered column by discount tier
- 🔘 **4 Interactive Slicers** — Filter by Region, Category, Segment, Ship Mode
- 📅 **Timeline Filter** — Drill into any time period dynamically
- ⚡ **All slicers connected to ALL Pivot Tables** simultaneously

---

## 🗂️ File Structure

```
superstore_project.xlsx
│
├── 📋 Orders          → Raw transaction data (source of truth)
├── 📊 KPIs            → Calculated KPI metrics
├── 🔍 Lookups         → Reference tables
├── 🧮 Analysis        → Supporting calculations
├── 📌 PT-Region       → Pivot: Sales by Region
├── 📌 PT-Category     → Pivot: Profit by Category
├── 📌 PT-Trend        → Pivot: Monthly Sales Trend
├── 📌 PT-Customers    → Pivot: Top 10 Customers
├── 📌 PT-Matrix       → Pivot: Discount Matrix
├── 📌 PT-Discount     → Pivot: Discount vs Profit
└── 🖥️ Dashboard       → Final interactive dashboard
```

---

## 🛠️ How It Was Built

### Step 1 — Data Preparation
- Cleaned raw Orders data
- Created a structured KPIs sheet with formula-driven metrics
- Built Lookup tables for consistent references

### Step 2 — Pivot Tables
Built 6 dedicated Pivot Tables, each on its own sheet, feeding one chart each. This keeps the dashboard clean and the data model organized.

### Step 3 — KPI Cards
Manually designed 4 KPI cards using merged cells, fill colors, and cell references linking to the KPIs sheet. Color-coded: Blue / Green / Orange / Red.

### Step 4 — PivotCharts
Each chart was built directly from its Pivot Table, then moved onto the Dashboard sheet and resized to fit the layout blueprint.

### Step 5 — Slicers & Timeline
- Inserted 4 slicers (Region, Category, Segment, Ship Mode)
- Inserted an Order Date Timeline
- Connected all slicers to all 6 Pivot Tables via **Report Connections**

---


## 💡 Key Business Insights

- 📍 **West region** leads in revenue at $7.25M
- 🪑 **Furniture** is the only category with significant losses — pricing strategy needed
- 💸 **High discount tiers** directly correlate with negative profit — discounting is destroying margins
- 👤 **Sean Miller** is the #1 customer by revenue at $25K
- 📅 **Q4 (Oct–Dec)** shows strong seasonal spikes every year — plan inventory accordingly

---

## 🧰 Tools Used

- Microsoft Excel (Office 2016)
- Pivot Tables & PivotCharts
- Slicers & Timelines
- Conditional Formatting
- Named Ranges & GETPIVOTDATA

---

## 📥 How to Use

1. **Download** `superstore_project.xlsx`
2. **Open** in Microsoft Excel (2016 or later recommended)
3. **Enable editing** if prompted
4. **Click any slicer** to filter the entire dashboard instantly
5. **Drag the timeline** to zoom into specific date ranges

---

## 🙋 About

Built as a portfolio project to demonstrate end-to-end data analytics skills using Excel — from raw data to executive-ready dashboard.

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If this helped you, please star the repo — it means a lot!**
