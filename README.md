📦 Inventory Dead Stock & Working Capital Leakage Analysis
📌 Project Overview

This project analyzes inventory health and working capital efficiency for a simulated FMCG distributor operating across multiple product categories and retail channels.

The objective is to identify:

Slow-moving and dead stock
Working capital blocked in aging inventory
SKU-level inefficiencies
Capital allocation risks across categories and brands
The solution combines Python (data generation & preprocessing), MySQL (data modeling & analysis), and Power BI (interactive dashboarding) to deliver executive-level insights.

🎯 Business Problem

In FMCG distribution, excess inventory directly impacts cash flow. Products that remain unsold for long durations (90+ days) tie up working capital and reduce operational efficiency.
Key questions addressed:
How much working capital is blocked in aging stock?
Which SKUs are overstocked relative to sales velocity?
Which categories have poor inventory turnover?
Are slow-moving products consuming disproportionate capital?

🏗 Data Model

The solution uses a structured relational model:
Dimension Tables
product_master
supplier_master
retailer_master
Fact Tables
sales_transactions
purchase_transactions
inventory_snapshot

The model follows a fact–dimension schema to enable scalable analytical queries.

⚙️ Tools & Technologies
Python (Pandas, NumPy) – Data generation & preprocessing
MySQL Workbench – Data modeling, SQL analysis
Power BI Desktop – Dashboard design & DAX calculations

📊 Key Metrics Built (DAX & SQL)
Total Revenue
Gross Profit
Gross Margin %
Working Capital Blocked
Inventory Turnover
Capital Efficiency Ratio
90+ Days Aging Analysis
SKU-Level Risk Identification

🔍 Key Insights

₹13.7M+ working capital identified as blocked in aging inventory.
90+ day stock contributes significantly to capital inefficiency.
Slow-moving SKUs show high capital blockage but low revenue contribution.
Category-level turnover variation highlights optimization opportunities.

📈 Dashboard Pages
1️⃣ Executive Overview

High-level KPIs and category-wise capital exposure.

2️⃣ SKU Risk & Operational Insights
SKU-level blocked capital, sales velocity comparison, and movement-type performance.

3️⃣ Efficiency & Operational Summary
Turnover analysis, aging breakdown, and brand-level capital concentration.

🧠 Business Impact
This analysis framework can help:
Reduce dead stock
Improve inventory turnover
Optimize capital allocation

📌 Project Scope
This project simulates a one-year inventory cycle for 170+ SKUs with purchase, sales, and inventory tracking across multiple retailers and categories.

Improve distributor cash flow visibility

Support data-driven procurement planning
