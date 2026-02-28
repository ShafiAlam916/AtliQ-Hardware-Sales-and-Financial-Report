# 📊 AtliQ Hardware Sales and Financial Report

---

## 🎥 LinkedIn Project Post

👉 I’ve shared a detailed breakdown of this project on LinkedIn, covering the reporting structure, financial insights, and sales performance analysis.

🔗 View the full post here:  
https://www.linkedin.com/posts/mdshafialam_happy-to-share-that-ive-completed-four-structured-activity-7412037032681582592-ghOA?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFANRrUB8YOiQ7CrZlkNSWAytjyAKghfpAs

---

## 🚀 Project Overview

This project focuses on building structured **Sales and Financial Reports** to enable data-backed decision-making for AtliQ Hardware.

The company lacked a centralized analytics structure, relying heavily on Excel-based reporting and intuition-driven decisions. To address this gap, I modeled the available datasets, structured relationships, and developed analytical reports to support leadership in evaluating performance across customers, markets, and fiscal periods.

The solution delivers four key business reports:

1️⃣ **Customer Net Sales Performance**  
Analyzes customer-level revenue contribution and performance trends.

2️⃣ **Market Performance vs Target**  
Compares actual net sales against predefined market-level sales targets.

3️⃣ **Profit & Loss (P&L) Report**  
Provides an overall financial summary including revenue, costs, and profitability.

4️⃣ **P&L by Fiscal Months**  
Tracks financial performance across fiscal months to identify seasonal trends and margin shifts.

These reports collectively support financial transparency, performance benchmarking, and strategic decision-making.

---

## 🏢 Company Overview

AltiQ Hardware is a fast-growing company operating in the global computer hardware industry. Over recent years, the organization has expanded its footprint across multiple international markets, offering computers and computer accessories through three primary sales channels:

- Retailers  
- Direct Sales  
- Distributors  

During its expansion into the American market, AltiQ Hardware encountered unexpected financial losses. Strategic decisions were largely driven by surveys, intuition, and limited Excel-based analysis, which restricted visibility into true business performance.

Meanwhile, competitors with mature analytics capabilities were leveraging data-driven insights to make faster, more accurate decisions, gaining a competitive edge. Recognizing this gap, AltiQ Hardware identified the urgent need to build a robust analytics foundation—one that could support informed decision-making, improve transparency, and strengthen its competitive position in a highly data-driven industry.

---

## 🗂️ Datasets Used

### 📌 Dimension Tables (Static Reference Data)

- **dim_customer**  
  Contains 75 customers across 27 markets (e.g., India, USA, Spain), operating on Brick & Mortar and E-commerce platforms, and selling through three channels: Retailer, Direct, and Distributor.

- **dim_market**  
  Defines the market hierarchy spanning 27 markets, 7 sub-zones, and 4 regions:  
  APAC, EU, LATAM, and North America (NA).

- **ns_targets_2021**  
  Contains market-level net sales targets by country and date.

---

### 📊 Fact Tables (Transactional Data)

- **fact_sales_monthly**  
  Stores monthly actual sales quantity at the customer and product level, forming the core dataset for performance and financial analysis.

---

## 🙌 Data Courtesy

Data provided by **Codebasics** for learning and project development purposes.
