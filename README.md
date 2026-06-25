# 🛡️ Prism Insurance Pvt. Ltd. — Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Tool:** Microsoft Power BI &nbsp;|&nbsp; **Domain:** Insurance Business Analytics  
> 

---

## 📌 About This Project

An end-to-end **Power BI analytics solution** built for **Prism Insurance Pvt. Ltd.** that delivers a 360° view of insurance operations — covering premium revenue, coverage exposure, claim distribution, policy activity, and customer demographics. Built with a sleek dark theme and full interactivity, it transforms raw insurance data into executive-ready intelligence.

---

## 📂 Repository Structure

```
Insurance_Dashboard/
│
├── 📊 Overview.png            ← Screenshot of the Overview (Summary) dashboard page
├── 📋 Detailed_Analysis.png   ← Screenshot of the Detailed Records drill-through page
└── 📁 InsuranceData.csv       ← Raw dataset used to build the dashboard
```

> 💡 **Quick navigation:**
> - Want to see the main dashboard? → [`Overview.png`](./Overview.png)
> - Want to see the data table / drill-through page? → [`Detailed_Analysis.png`](./Detailed_Analysis.png)
> - Want the raw data? → [`InsuranceData.csv`](./InsuranceData.csv)

---

## 🖥️ Dashboard Pages

### Page 1 — Overview (Summary Dashboard)

> 📸 **Screenshot:** [`Overview.png`](./Overview.png)

The command center of the dashboard. All mission-critical KPIs and charts visible at a glance.

**KPI Cards:**

| Metric | Value |
|--------|-------|
| 💰 Total Premium Amount | 5.98M |
| 🛡️ Total Coverage Amount | 600.55M |
| 📋 Total Claim Amount | 16.91M |
| 👩 Female Policyholders | 5,001 |
| 👨 Male Policyholders | 5,003 |

**Visuals Included:**

- **Premium Amount by Policy Type** *(Horizontal Bar Chart)* — Travel leads at 2.5M, followed by Health (1.2M), Auto (1.0M), Life (0.7M), and Home (0.6M)
- **Active vs Inactive Policies** *(Donut Chart)* — Active policies at 5.82K (58.13%), Inactive at 4.19K (41.87%)
- **Number of Claims by Claim Status** *(Area Chart)* — Rejected: 4.4K | Settled: 3.4K | Pending: 2.3K — highlighting a critical gap between rejections and settlements
- **Claim Amount by Age Group** *(Line Chart)* — Adults carry the heaviest burden at 8.8M, Elders at 6.4M, Young at 1.7M
- **Policy Type × Claim Status Matrix** *(Table)* — Full breakdown of Pending, Rejected, and Settled amounts across Auto, Health, Home, Life, and Travel for precise cross-dimensional analysis

**Dropdown Slicers:** PolicyNumber / ClaimNumber / CustomerID — filter every visual in real time

---

### Page 2 — Detailed Records (Drill-Through)

> 📸 **Screenshot:** [`Detailed_Analysis.png`](./Detailed_Analysis.png)

A fully scrollable, policy-level data table for granular investigation.

**Columns:** PolicyNumber, CustomerID, ClaimNumber, Age, Gender, CoverageAmount, PremiumAmount, PolicyStartDate, PolicyEndDate, PolicyType, ClaimStatus, ClaimDate

- Date range spans **2023–2025** across all policy types
- Supports analyst-level investigation, compliance checks, and individual claim audits
- Back navigation arrow (←) for seamless return to the overview page

---

## 🔍 Interactive Features

| Feature | Description |
|---------|-------------|
| **Dropdown Slicers** | Filter entire dashboard by PolicyNumber, ClaimNumber, or CustomerID — all visuals update dynamically |
| **Cross-Visual Filtering** | Clicking any chart element instantly cross-filters all other visuals |
| **Drill-Through Navigation** | Right-click any data point → navigate to the Detailed Records page for full policy-level context |
| **Context Menu** | Show as Table, Include/Exclude filters, and New Visual Calculation for on-the-fly exploration |
| **Reset / Blank State** | Cleanly resets all slicers and visuals back to unfiltered view |

---

## ⚙️ Technical Highlights

| Category | Details |
|----------|---------|
| **Tools** | Microsoft Power BI, DAX, Power Query, Data Modeling |
| **Features** | Dynamic KPI Cards, Dropdown Slicers, Cross-Visual Filtering, Drill-Through, Matrix Tables, Scrollable Detail Pages |
| **Design** | Dark monochrome theme — near-black canvas, teal/mint accent for active data, amber for inactive, clean white typography |
| **Dataset** | `InsuranceData.csv` — 10,000+ records covering policyholders from 2023–2025 |

---

## 💡 Business Value

This dashboard empowers insurance analysts, risk managers, and operations leaders to:

- 📌 Instantly identify which policy types generate the highest premium and claim volumes
- 📌 Monitor the Active vs Inactive policy split to assess portfolio health and renewal risk
- 📌 Analyze claim rejection vs settlement ratios to flag underwriting inefficiencies
- 📌 Benchmark claim exposure across age groups for better actuarial risk segmentation
- 📌 Drill into individual policyholder records for compliance, dispute resolution, or audit trails

---

## 📬 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Het%20Ladani-blue?logo=linkedin)](https://linkedin.com/in/het-ladani-5001bb29a/)
[![GitHub](https://img.shields.io/badge/GitHub-ladanihet2410-black?logo=github)](https://github.com/ladanihet2410)