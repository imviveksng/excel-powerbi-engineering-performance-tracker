# 📊 Engineering Team Performance Tracker (Excel + Power BI)

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi)
![Excel](https://img.shields.io/badge/Data-Excel-217346?style=for-the-badge&logo=microsoftexcel)
![Status](https://img.shields.io/badge/Status-Live%20Project-brightgreen?style=for-the-badge)

## 📊 Project Overview
A real-world performance tracking system built for an 
engineering detailing team of **32+ members** across 6 team leads.
Tracks drawing submissions (AB&GA) and BOQ targets vs actuals 
with capacity and attrition impact analysis.

---

## 🔧 Tools Used
- **Microsoft Excel** — Master data input and tracking
- **Power BI** — Interactive dashboards and KPI visualization
- **Power Query** — Data transformation and calculated columns
- **DAX** — Custom measures for % achievement, shortfall, capacity

---

## ⚙️ Key Features
- 📌 Individual + Team-level target vs achieved tracking
- 📉 Attrition impact analysis (tonnage lost due to resignations)
- 🧮 Real capacity vs organizational goal gap calculation
- 🔄 Revised targets based on actual joining dates
- 👥 Team lead performance leaderboard
- 📊 AB&GA% and BOQ% completion KPIs per member

---

## 📈 Key Metrics Tracked

| KPI | Value |
|-----|-------|
| Organization Goal (AB&GA) | 70,000 |
| Rostered Target | 67,000 |
| Real Capacity | 55,522 |
| Actual Achieved | 47,100 |
| Lost to Attrition | 5,038 |
| Total Shortfall | 14,478 |
| Active Detailers | 32 |

---

## 🧠 Business Logic Implemented
Real Capacity = Rostered Target - Hiring Gap - Lost to Attrition
Total Shortfall = Org Goal - Real Capacity
Revised Target = Prorated based on joining date
Achievement % = Actual Achieved / Revised Target × 100
---

## 📊 Dashboard Sections
1. **Team Summary** — All 6 TLs with AB&GA% and BOQ% at a glance
2. **Individual Tracker** — Per-member target, revised target, achieved
3. **Attrition Impact Panel** — Resigned members and tonnage lost
4. **Capacity Analysis** — Org goal vs real capacity vs achieved
5. **Outsourced Work** — Received vs pending outsourced tonnage

---

## 📸 Dashboard Preview
![Overview](screenshots/BI%20Fresh.PNG) 
![Team Performance](screenshots/Excel%20Jobs%20Pivot.PNG)

---

## 🚀 How to Use
1. Download `FY 2025-2026.xlsx` from `/data`
2. Open `dashboard.pbix` from `/files` in Power BI Desktop
3. Refresh data source to point to the Excel file
4. Use slicers to filter by Team Lead or Status

---

## 📌 Business Impact
- Enabled management to identify **underperforming teams early**
- Quantified attrition cost in measurable tonnage units
- Provided data-backed justification for **replacement hiring**
- Reduced manual reporting time from hours to minutes

---

## 🤝 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/vivek-kumar-singh-2b41bb229/)
