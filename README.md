# Superstore Sales Performance Dashboard (Power BI)

Data Science & Analytics – Task 1 | Future Interns

## Dashboard preview
![Overview](screenshots/page1_overview.png)
![Products](screenshots/page2_products.png)
![Regions and Discounts](screenshots/page3_regions_discounts.png)
![Insights](screenshots/page4_insights.png)

## Business problem
Which products, categories and regions drive revenue and profit, how do sales change over time, and where should the business focus to grow faster?

## Dataset
Sample Superstore (Kaggle): 9,994 order lines, 2014–2017, United States. No missing values or duplicates were found.

## Tools
Power BI Desktop, Power Query, DAX

## Process
1. Loaded the CSV (Windows-1252 encoding) and set data types, with dates parsed in US format.
2. Built a Date table and related it to Order Date.
3. Created a Discount Band column and DAX measures: Total Sales, Total Profit, Profit Margin %, Orders Count, Customers, Sales LY, Sales YoY %.
4. Built a 4-page dashboard: Overview, Products, Regions & Discounts, Insights.

## Key results
| Metric | Value |
|---|---|
| Sales | $2.30M |
| Profit | $286K |
| Margin | 12.5% |
| Orders / Customers | 5,009 / 793 |

## Insights
- Sales grew from $484K (2014) to $733K (2017); margin has held around 13% since 2014.
- Technology (17.4% margin) and Office Supplies (17.0%) generate 93% of profit; Furniture earns only 2.5%.
- Orders discounted by more than 20% lost about $135K in total, nearly half of total profit.
- Tables (−$17.7K), Bookcases and Supplies are loss-making.
- Central region margin is 7.9% versus 14.9% in the West. Texas, Ohio, Pennsylvania, Illinois and North Carolina lose about $78K together.
- Sales peak in September–December.

## Recommendations
1. Cap discounts at 20%, with approval required above it.
2. Reprice or renegotiate supplier costs for Furniture, especially Tables.
3. Tighten discounting in the loss-making states.
4. Promote high-margin products (Copiers, Paper, Accessories) and grow the West and East.
5. Plan stock and campaigns around the Q4 peak.

## Files
- `FUTURE_DS_01.pbix`: Power BI report
- `FUTURE_DS_01.pdf`: exported report (all 4 pages)
- `screenshots/`: page images
- `Sample - Superstore.csv`: source data
