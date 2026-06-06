# E-Commerce Sales Analytics Dashboard

## 📌 Project Overview
[cite_start]This project focuses on transforming raw, fragmented retail sales data into a centralized, interactive analytics dashboard[cite: 121]. [cite_start]The primary goal is to perform a financial integrity audit, isolate key profitability drivers, evaluate demographic concentrations, and detect regional market expansion opportunities to optimize bottom-line business performance[cite: 121, 128, 131, 132, 133].

## 📊 Live Dashboard Preview
(dashboard_screenshot.png)

## 🛠️ Tech Stack & Tools Used
* [cite_start]**Data Transformation & Auditing:** MS Excel (`XLOOKUP`, `PROPER`, `TRIM` functions) [cite: 126, 127]
* [cite_start]**Data Summarization:** Advanced Pivot Tables [cite: 137, 138]
* [cite_start]**Data Visualization & Analytics:** Power BI Dashboard / MS Excel Charting Engines [cite: 142, 143]

## 📈 Key Business Performance Indicators (KPIs)
[cite_start]The dashboard features a centralized executive KPI ribbon highlighting[cite: 143, 144]:
* [cite_start]**Total Revenue:** ₹2.17M [cite: 144]
* [cite_start]**Total Profit:** ₹1.66M [cite: 144]
* [cite_start]**Profitability Percentage:** 86.8% [cite: 144]
* [cite_start]**Loss Transaction Count:** Tracks instances where heavy discounts led to negative margins[cite: 131, 144].

## 🔍 Data Cleaning & Pipeline Implementation (Solo Developer)
As the sole owner of this project's analytical pipeline, I executed the following end-to-end steps:
1. [cite_start]**Missing Value Resolution:** Discovered missing cost values for six items in the product dimensions table[cite: 124]. [cite_start]Resolved this by applying an **Average Cost Imputation** mapped directly to their specific sub-categories[cite: 125].
2. [cite_start]**Text Standardization:** Utilized `TRIM` and `PROPER` text formatting operations to eliminate irregular spacing and inconsistent letter casings across customer and store identifier fields[cite: 126].
3. [cite_start]**Relational Schema Mapping:** Used `XLOOKUP` arrays to establish clean relationships, bridging separate customer, product, and physical store logs into a singular unified Master Fact Table[cite: 127].

## 💡 Key Strategic Insights
* [cite_start]**Discount Vulnerabilities:** Isolated distinct transaction losses (accounting for 13.2% of overall orders) driven entirely by over-aggressive discounting metrics applied to low-volume checkouts[cite: 131].
* [cite_start]**Core Demographics:** Identified that the **Middle Age** group combined with **Platinum Loyalty Tiers** act as the primary structural revenue anchors for the business[cite: 132].
* [cite_start]**Geographic Expansion:** Uncovered a severe underperformance in the **West Region**, which yields just 12.6% of overall revenue metrics, highlighting it as a prime target for local marketing initiatives[cite: 133].
* [cite_start]**Multichannel Footprint:** Established that digital, online checkouts safely outperform traditional flagship venues, capturing over 41% of total ongoing transaction volume[cite: 134, 135].

## 🎯 Final Business Recommendations
1. [cite_start]Re-evaluate discount thresholds on low-quantity baskets to automatically secure leaking profit margins[cite: 151].
2. [cite_start]Redirect strategic marketing budgets toward the **West Region** to scale market presence where the brand is underrepresented[cite: 133, 151].
