# Amazon Sales Data Analysis - ACC102 Course Project

## 1. Problem & User
The core analytical problem is exploring Amazon sales structure, fulfilment channel efficiency and revenue contribution rules across different price segments. The intended users of this report are e-commerce operational managers and financial analysts, who need data conclusions to adjust pricing strategies and logistics allocation plans.

## 2. Data
- Data source: Public Amazon online order sales dataset（from kuggle）
- Data access date: April 2026
- Total records: 128,975 rows
- Key fields: Order ID, transaction amount (Amount), order quantity (Qty), fulfilment logistics type, order date, product category, price level classification

## 3. Methods
1. Data cleaning: Check missing values, delete high-missing invalid columns, filter abnormal dirty data
2. Data grouping & statistics: Group orders by price level and fulfilment channel, calculate total sales, order count and average amount
3. Correlation analysis: Build correlation matrix between core sales numeric variables
4. Data visualisation: Draw bar charts, pie charts and heatmaps to show multi-dimensional business results

## 4. Key Findings
- High-price orders contribute the largest proportion of total platform sales revenue, becoming the core profit source
- Amazon official fulfilment occupies dominant share in both total order volume and overall sales amount
- Average customer unit price of Amazon delivery and Merchant self-delivery channels is almost identical
- Order quantity and transaction amount show strong positive linear correlation
- Medium & low-price orders account for most order numbers, but have low single-order revenue contribution

## 5. How to run
1. Download all files from this repository
2. Install dependent libraries: pandas, matplotlib, seaborn
3. Open and run the full code sequentially in ACC102_Track2_AmazonSales.ipynb with Jupyter Notebook
4. All statistical results and charts will be generated automatically

## 6. Product link / Demo
GitHub Repository: https://github.com/Wen7729/Amazon-sale-data

## 7. Limitations & next steps
- Limitations: Lack of long-term time-series data, cannot analyse seasonal sales fluctuation rules; no advertising and inventory related indicators included
- Next steps: Add time trend analysis by month, conduct cross-dimensional analysis between product categories and price levels, build deeper sales forecasting model
