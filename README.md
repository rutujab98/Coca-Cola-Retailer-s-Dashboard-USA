# 🥤 Coca-Cola Retailer's Dashboard USA (Excel)

## 🧾 Overview
This project presents a visually rich, interactive **Excel dashboard** analyzing Coca-Cola’s retail performance across **two years (2022–2023)** in the United States. It tracks critical business metrics such as **Total Sales**, **Units Sold**, **Operating Profit**, **Average Price per Unit**, and **Operating Margin** across five U.S. regions.

The dashboard is designed for fast decision-making, with comparisons across years, retailers, and beverage brands—backed by interactive slicers and engaging visuals.

---

## 📁 Dataset Summary

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| Retailer             | Retail partner name (e.g., Amazon, BevCo)        |
| Invoice Date         | Date of sale (used to extract year/quarter)      |
| Region               | Region of transaction (e.g., Northeast, West)    |
| Beverage Brand       | Coca-Cola brand sold (e.g., Fanta, Sprite)       |
| Units Sold           | Total items sold                                 |
| Price per Unit       | Selling price per unit                           |
| Total Sales          | Revenue (Units × Price)                          |
| Operating Profit     | Profit after deducting operational costs         |
| Operating Margin     | Profit ÷ Sales (expressed as percentage)         |

---

## 📊 Key Metrics Displayed (KPI Cards)

| Metric              | Value            |
|---------------------|------------------|
| 💰 **Total Sales**   | $12,016,665       |
| 📦 **Units Sold**     | 24,788,610 units |
| 💵 **Avg Price/Unit**| $0.45             |
| 📈 **Operating Profit** | $4,722,497     |

---

## 🧰 Filters (Slicers Used)

- 📆 **Years (Invoice Date)**: `2022`, `2023`
- 🌍 **Region**: `Midwest`, `Northeast`, `South`, `Southeast`, `West`

These filters allow users to analyze trends and KPIs interactively by time period and region.

---

## 📈 Visuals & Charts Used

| Visual                | Purpose                                                       |
|-----------------------|---------------------------------------------------------------|
| **Table: Sales by Retailer**       | Year-wise performance & variance for top 6 retailers        |
| **Table: Sales by Beverage Brand** | Year-wise comparison of top 6 Coca-Cola brands              |
| **Clustered Column Chart + Line**  | Operating Profit & Margin by Quarter (2022 & 2023)          |
| **KPI Cards**                      | Top-level summary of key performance metrics                |
| **Slicers**                        | Region and Year-based interactivity                         |

---

## 💡 Key Insights

### 📊 Year-over-Year Growth
- **Total Sales increased by $453,268** from 2022 to 2023.
- **Operating Profit and Margin** steadily increased each quarter, peaking in **Q3 2023** with highest profits and a margin of **44%**.

### 🛒 Retailer Performance
| Retailer     | Insight                                                |
|--------------|---------------------------------------------------------|
| ✅ **West Soda**   | Highest overall sales ($952K in 2022, $864K in 2023) despite a drop in 2023. |
| ✅ **BevCo**       | Maintained strong sales ($628K → $587K), but saw a **negative variance**.     |
| ✅ **FizzyCo**     | Showed **highest positive growth** (+$211K), though overall volume was low.  |
| ✅ **Target & Walmart** | Moderate growth with **Target** increasing by $99K and **Walmart** by $190K. |
| ❌ **BevCo and West Soda** experienced sales drop in 2023. |

### 🥤 Beverage Brand Insights
- **Coca-Cola** led in brand sales, growing by **$113K** in 2023.
- **Dasani Water** saw the **largest increase**: +$196K.
- **Diet Coke**, **Fanta**, **Powerade**, and **Sprite** also showed positive year-on-year growth.
- Brand sales growth was consistent across the board, reflecting **brand equity and stable pricing**.

### 💹 Operating Profit & Margin by Quarter
- **Operating Profit rose steadily** from **Q1 2022 to Q3 2023**, peaking just above $1.1M.
- **Operating Margin** also climbed, reaching **44% in Q3 2023**, showing improved cost management and profitability.
- Slight dip observed in **Q4 2023**, but overall annual margin remained high.

---

## 🛠 Tools Used

- **Microsoft Excel**
  - Pivot Tables & Pivot Charts
  - KPI Cards using formulas
  - Tables for year-over-year variance tracking
  - Slicers for Region and Year
  - Combined Column + Line Chart (Operating Profit & Margin)
  - Conditional Formatting for highlighting variance
  - Dashboard layout with brand colors and formatting

---

## 📷 Dashboard Preview

![Coca-Cola Dashboard](images/coca-dashboard-preview.png)
