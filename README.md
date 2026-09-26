# Sales Performance Dashboard

Interactive Power BI dashboard analyzing 51K+ global retail orders (2011–2014) across sales, products, regions, and customers.

## Overview
A 4-page Power BI dashboard built on the Global Superstore dataset, designed to explore sales performance, profitability, and customer behavior across 7 global markets. Built as a portfolio project to demonstrate data cleaning, data modeling, DAX, and dashboard design skills.

## Data Source
Global Superstore dataset (Kaggle) — 51,290 orders, 21 columns, spanning 2011–2014 across Africa, APAC, Canada, EMEA, EU, LATAM, and US markets.

## Tools Used
- Power BI Desktop (Power Query, Data Modeling, DAX)

## What I Did
- Cleaned raw data in Power Query: converted text-formatted sales values to numbers, standardized two mixed date formats
- Built a star-schema-style data model with a dedicated Date table
- Created DAX measures: Total Sales, Total Profit, Profit Margin %, Total Orders, Year-over-Year Growth
- Designed 4 report pages:
  - **Executive Overview** — KPI cards, monthly sales trend
  - **Product Analysis** — sales/profit by category & sub-category, top and bottom 10 products by profit
  - **Regional Analysis** — sales by country (map), market comparison, regional summary table
  - **Customer Analysis** — top 10 customers, sales by segment
- Added synced slicers (Year, Market, Category) across all pages for consistent cross-filtering

## Key Insights
1. **Category performance:** Technology is the strongest category by profit despite lower sales than Furniture, while Furniture generates the weakest profit relative to its sales.
2. **Products with losses:** A handful of products consistently operate at a loss, with Chromcraft Bull Nose, Bevis Wood Table, and Lesro Training Table showing the largest negative profits (~$2.6K–$2.9K each).
3. **Regional performance:** Canada has the highest profit margin (~26.6%) despite the smallest sales volume, notably ahead of APAC, EU, US, and Africa (11–13%).
4. **Market & segment contribution:** APAC and EU are the top two markets by sales, together driving over half of total revenue. The Consumer segment leads in both sales (~6.5M) and profit (~0.7M).
5. **Trend:** Sales grew steadily from 2011 to 2014, with recurring peaks toward year-end.

## Files
- `Sales_Performance_Dashboard.pbix` — the full interactive report (open in Power BI Desktop to use the live filters)
- `Sales_Performance_Dashboard.pdf` — static export of all report pages

## Screenshots
![Executive Overview](page1-executive-overview.png)
![Product Analysis](page2-product-analysis.png)
![Regional Analysis](page3-regional-analysis.png)
![Customer Analysis](page4-customer-analysis.png)
