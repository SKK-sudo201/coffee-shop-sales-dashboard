## ☕ Coffee Shop Sales Analysis | Excel Dashboard Project
Created an interactive Excel dashboard analyzing coffee shop transaction data across **three NYC locations** to uncover **sales trends, peak hours, and top-performing products**.

## PROJECT OVERVIEW
This project analyzes **149,116 individual transactions** ($698,812 in total revenue) from **Maven Roasters**, a coffee business operating three NYC locations (Astoria, Hell's Kitchen, Lower Manhattan), over 6 months (January 2023 - June 2023). The dashboard was built using **PivotTables, Pivot Charts, and slicers** for dynamic, location-level filtering.

## PROJECT RESULTS
| Metric | Result |
|---|---|
| Total transactions analyzed | 149,116 |
| Total revenue | $698,812 |
| Date range | Jan 1 - Jun 30, 2023 |
| Revenue growth (Jan → Jun) | $81,678 → $166,486 (+104%) |
| Store performance spread | Astoria $232K / Hell's Kitchen $236.5K / Lower Manhattan $230K (within 3% of each other) |
| Peak sales hours | 7 AM - 10 AM, with 10 AM as the single busiest hour |
| Top category by volume | Coffee —> 89,250 items sold, followed by Tea at 69,737 |
| Top revenue-driving product | Barista Espresso —> $91,406 total revenue |
| Top volume product | Brewed Chai Tea —> 17,183 transactions |
| Busiest day (overall) | Friday, closely followed by Thursday and Monday |

## PROJECT OBJECTIVES
1.	PREPARE THE DATA FOR ANALYSIS
2.	EXPLORE THE DATA WITH PIVOT TABLES
3.	BUILD A DYNAMIC DASHBOARD

## PROJECT WORKFLOW
1.	**Data Cleaning & Modeling**: Structured raw transaction-level data (date, time, store, product, quantity, price) for PivotTable analysis
2.	**Time-Series Analysis**: Tracked monthly revenue trends across the full 6-month period
3.	**Peak-Hour Analysis**: Identified hourly and day-of-week transaction patterns to surface demand peaks
4.	**Product Performance Analysis**: Ranked all products by both transaction volume and total revenue to separate "high-frequency" from "high-value" items
5.	**Location Comparison**: Built a slicer-driven dashboard enabling instant filtering between all 3 store locations
6.	**Interactive Dashboard Design**: Combined Pivot Charts, slicers, and a top-15 product table into a single, stakeholder-ready Excel dashboard

## DATASET
The dataset (`coffee_shop_sales.csv`) contains the following fields:
1.	`transaction_id` —> unique transaction identifier
2.	`transaction_date` / `transaction_time` —> date and time of sale
3.	`transaction_qty` —> quantity of items in the transaction
4.	`store_id` / `store_location` —> store identifier and NYC location name
5.	`product_id` / `product_category` / `product_type` / `product_detail` —> product classification hierarchy
6.	`unit_price` —> price per unit (USD)

## TOOLS & SKILLS
Microsoft Excel · PivotTables · PivotCharts · Slicers · Data Cleaning · Time-Series Analysis · Dashboard Design · Business Intelligence

## BUSINESS INSIGHTS
1.	Revenue more than doubled over 6 months, with the sharpest single-month jump between April and May —> a trend worth flagging early for a growing business
2.	Sales are heavily concentrated in the morning commute window (7 AM - 10 AM), with a steady falloff through the afternoon and evening —> a clear staffing and inventory-timing signal
3.	Barista Espresso and Brewed Chai Tea lead on two different dimensions —> Espresso drives the most total revenue, while Chai Tea has the highest transaction count —> showing the value of tracking both metrics, not just one
4.	Tea makes up a larger share of the business than typically expected for a "coffee shop," nearly matching coffee in transaction volume
5.	All three store locations perform within 3% of each other, indicating a consistent, repeatable business model rather than one outlier location carrying performance
6.	Bakery products performed well as supporting items and are likely to help increase average order value when paired with beverages.

## RECOMMENDATIONS
1.	Increase staffing and inventory preparation during peak morning hours to improve service speed and customer experience.
2.	Review evening operating hours, especially for the Lower Manhattan location, to reduce unnecessary operational costs during low-demand periods.
3.	Continue promoting high-performing products like espresso beverages, brewed coffee, and tea through combo offers or seasonal specials.
4.	Introduce coffee and bakery combo deals during morning hours to encourage larger purchases.
5.	Use hourly sales trends to optimize staffing schedules and improve overall operational efficiency.

## Dashboard Screenshots
<img width="796" height="836" alt="dashboard_hell&#39;s_kitchen_location" src="https://github.com/user-attachments/assets/fcca98e6-75e0-4c90-b763-a0e00e3f5f60" />
<img width="792" height="842" alt="dashboard_Astoria_location" src="https://github.com/user-attachments/assets/39afba35-3a1e-4760-94b1-d6d9efef48d1" />
<img width="502" height="401" alt="top_products" src="https://github.com/user-attachments/assets/62d79587-355d-4950-ac68-47cba49eab54" />
<img width="502" height="397" alt="sales_by_hour" src="https://github.com/user-attachments/assets/dd40e884-c717-49ed-8a67-7b85bbe373f9" />
<img width="715" height="232" alt="revenue_by_month" src="https://github.com/user-attachments/assets/da7ea064-b69f-4add-92ff-69f2c2b40481" />
<img width="795" height="840" alt="dashboard_Lower_Manhattan_location" src="https://github.com/user-attachments/assets/16f94c5e-9b5f-40d9-9457-6d891c5a3b29" />
