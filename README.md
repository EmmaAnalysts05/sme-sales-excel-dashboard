# SME Retail Sales Performance Dashboard (Excel)

### 🔗 Project Links
* [Download Interactive Excel Workbook](SME_Sales_Dashboard.xlsx) 
*(Note: This workbook contains the raw data layer, analytical pivot engines, and the interactive frontend dashboard in a single unified file)*

---

## 📌 Project Overview
This repository showcases an end-to-end **SME Retail Sales Dashboard** engineered entirely inside **Microsoft Excel**. Built from an operational transactional database of 1,000 continuous consumer interactions, this project transforms messy retail records into structured, executive-ready corporate intelligence. 

The dashboard tracks commercial outputs across three key verticals: **Electronics, Clothing, and Beauty**. It provides a central control panel for business owners to audit month-over-month sales velocity, unit shipment volumes, and consumer demographic behaviors.

---

## 📊 Core Business Metrics Surfaced
Through formulas and Pivot Data architectures, the model extracts five strategic baseline anchors directly from the data:
* **Total Sales Revenue:** \$456,000
* **Cost of Goods Sold (COGS):** \$179,890
* **Gross Profit Margin:** 60.55%
* **Total Quantities Shipped:** 2,514 units
* **Active Unique Customer Base:** 1,000 buyers
* **Customer Base Average Age:** 41.39 years

---

## 📸 Dashboard Previews
![Excel Interactive Dashboard Overview](assets/dashboard-overview.png)
*Figure 1: Dynamic Excel dashboard tab utilizing Slicers, interactive KPI card tiles, and structured pivot visual graphs.*

![Pivot Architecture and Summary Tables](assets/pivot-worksheets.png)
*Figure 2: Dedicated backend worksheets hosting automated Pivot Tables for cohort segmentation and time-series extraction.*

---

## 💡 Key Analytical Insights & Strategic Recommendations

### 1. High-Value vs. High-Volume Disconnect
* **The Insight:** **Electronics** yields the company's highest categorical turnover value (**\$156,905**), but **Clothing** dominates operational inventory throughput with **894 total items moved**.
* **Strategic Recommendation:** Optimize cash-flow allocation. Maintain lean, just-in-time logistics for expensive Electronic items to limit tied-up capital, while negotiating volume bulk discounts on fast-moving Clothing stocks.

### 2. Time-Series Volatility & Demand Seasonality
* **The Insight:** Revenue tracks with severe seasonal shifts. Monthly sales hit massive peaks in **May (\$53,150)** and **October (\$46,580)**, contrasting sharply against a steep drop-off valley in **September (\$23,620)**.
* **Strategic Recommendation:** Schedule defensive promotion cycles. Deploy aggressive clear-out campaigns during August and September to stabilize the seasonal revenue dip, and pre-order inventory 30 days ahead of the massive May shopping surge.

### 3. Symmetrical Demographics & Purchasing Patterns
* **The Insight:** The retail audience splits almost perfectly between genders (**510 Female buyers vs. 490 Male buyers**). Furthermore, average buyer age sits identically close around **41.4 years old** for both groups.
* **Strategic Recommendation:** Abandon narrow, gender-segregated marketing spend. Pivot visual and digital budgets toward lifestyle campaigns highlighting utility and longevity, aimed at the core 35–45 year old family buyer cohort.

---

## 🛠️ Excel Workbook Architecture
The project is built as a self-contained corporate reporting tool structured into three functional sheet layers:

1. **📊 Frontend Dashboard Tab:** The executive interface featuring clean charting modules, custom-masked metric KPIs, and unified slicer controls for data discovery.
2. **🧼 Analytical Backend Tab:** Contains automated Pivot Tables parsing seasonal demand shifts, sales totals, item volumes, and age-demographic averages.
3. **📁 Raw Data Layer:** The foundational source containing 1,000 unedited consumer sales records across 10 operational columns.

---

## 🚀 Technical Features Used
* **Pivot Modeling & Aggregations:** Multi-dimensional matrix structures isolating sums, rolling counts, and calculated gender averages.
* **Custom Number Masking:** Handled high-density cell values via advanced Excel layout logic (`[>=1000000]$0.00,,"M";[>=1000]$0.00,"K";$0`) to guarantee executive report scannability.
* **UI Customization:** Gridline suppression and customized palette sync to mimic modern enterprise software interfaces.
