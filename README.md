# MH London (Power BI Dashboard)

## Overview
This project showcases a Power BI dashboard built using sales data imported from Excel. It provides insights into sales performance, product categories, regional trends, and seasonal patterns.

## Data Sources
The dashboard uses three datasets:
1. *Date Calendar Sheet*: Details on date, week, month, quarter, year, day status, and seasons.
2. *Raw Sales Data*: Includes PO date, SKU, quantity, per unit price, warehouse region, sales channel, and destination country.
3. *SKU Details*: Contains SKU, category, and type information.

## Steps Performed
1. Imported the datasets into Power BI.
2. Established table relationships:
   - Linked SKU between Raw Sales and SKU Details.
   - Linked PO Date to the Date column in the Calendar sheet.
3. Built simple yet effective visualizations:
   - Total Sales metrics
   - Monthly and regional sales trends
   - Product category and type analysis
   - Seasonal and quarterly sales patterns

## Visualizations
The dashboard features:
- *Cards*: Highlighting key metrics like total sales.
- *Line Charts*: Showing sales trends over time.
- *Bar Charts*: Comparing sales across regions and categories.
- *Pie Charts*: Displaying sales channel distribution.
- *Tree Maps*: Representing product type performance.

## Usage
- Open the Power BI file to view the dashboard.
- Use slicers and filters to explore the data dynamically.

## Files in Repository
- sales_data.xlsx: Source Excel file with raw data.
- PowerBI_Dashboard.pbix: The Power BI dashboard file.
