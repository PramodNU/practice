# Sales Performance & Business Analytics Dashboard (Power BI)

## Project overview
Build an interactive Power BI report for a fictional Indian retail business. It helps management monitor sales, profitability, order volume, product performance and regional trends.

**Dataset note:** The accompanying starter dataset contains 1,200 synthetically generated order rows for Jan 2024–Dec 2025. It is illustrative practice data, not real company/customer data. Values are in INR.

## Business questions
1. What are total sales, total profit, order count and profit margin?
2. How do sales and profit trend over time and year over year?
3. Which categories, sub-categories and products contribute most to sales and profit?
4. Which regions and states perform best?
5. How do customer segments compare?
6. How does discounting relate to profitability?

## Tools
- Microsoft Power BI Desktop
- Power Query
- DAX
- GitHub

## Project files
- `sales_data.csv` — synthetic practice dataset
- `DAX_measures_and_date_table.txt` — suggested DAX measures and Date table
- `data_dictionary.csv` — column descriptions and data types
- `dashboard_build_guide.md` — report page specifications

## Build steps
1. Import `sales_data.csv` into Power BI Desktop.
2. Set data types in Power Query and check for missing values/duplicate order IDs.
3. Create a Date table and measures from the DAX file.
4. Relate Date[Date] to Sales[Order_Date].
5. Build the three pages in the dashboard guide.
6. Validate KPI totals against the source data.
7. Save the finished report as `Sales_Performance_Dashboard.pbix`.
8. Add screenshots to an `Images/` folder and document actual insights.

## Report pages
### Executive Overview
KPI cards for Total Sales, Total Profit, Total Orders and Profit Margin; monthly trend; category and regional comparisons. Add Year, Region and Customer Segment slicers.

### Product Performance
Top 10 products, category/sub-category treemap, and a matrix showing Sales, Profit and Profit Margin.

### Regional & Customer Analysis
State-level sales, regional profit, customer segment mix and a region/segment matrix.

## Resume entry — use only after completing and validating the report
**Sales Performance & Business Analytics Dashboard | Power BI**
- Developed an interactive three-page Power BI dashboard to analyze sales, profitability, product performance and regional trends using a 1,200-row synthetic retail dataset.
- Cleaned and transformed data using Power Query and created DAX measures for sales, profit, order count, profit margin and year-over-year analysis.
- Designed KPI cards, trend charts and category/region breakdowns with interactive slicers to explore business performance.

## Important
This is a self-directed portfolio project using synthetic data. Do not describe it as professional client work. Do not claim the report is complete until the PBIX has been built, tested and uploaded.
