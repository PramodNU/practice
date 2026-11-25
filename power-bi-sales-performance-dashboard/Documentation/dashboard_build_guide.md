# Dashboard Build Guide

## Data model
Use a Sales fact table and a Date dimension.
- Relationship: Date[Date] (1) -> Sales[Order_Date] (*)
- Use a single-direction filter from Date to Sales.

## Page 1 — Executive Overview
**KPI cards:** Total Sales, Total Profit, Total Orders, Profit Margin %.

**Visuals:**
- Line chart: Total Sales by Date[Year-Month].
- Clustered column chart: Total Sales and Total Profit by Category.
- Bar chart: Total Sales by Region.

**Slicers:** Year, Region, Customer Segment.

## Page 2 — Product Performance
**Visuals:**
- Bar chart: Top 10 Products by Total Sales (apply a visual-level Top N filter).
- Treemap: Total Sales by Category and Sub_Category.
- Matrix: Category > Sub_Category with Total Sales, Total Profit and Profit Margin %.
- Optional scatter chart: Sales vs Profit by Product.

**Slicers:** Category and Sub_Category.

## Page 3 — Regional & Customer Analysis
**Visuals:**
- Bar chart: Total Sales by State.
- Column chart: Total Profit by Region.
- Donut chart: Total Sales by Customer Segment.
- Matrix: Region and Customer Segment with Total Orders, Total Sales and Profit Margin %.

**Slicers:** Year and Region.

## Formatting and validation checklist
- Use a consistent theme and restrained colors.
- Format Sales and Profit as INR currency.
- Format Profit Margin % and YoY % as percentages.
- Sort Year-Month chronologically.
- Add descriptive visual titles.
- Test slicers and cross-filtering across pages.
- Reconcile card totals with the source data before publishing.

## Insights
Record only findings visible in the completed dashboard. Examples include the leading category by sales, strongest region by profit, highest-sales month, most profitable product, and discount/profitability patterns.
