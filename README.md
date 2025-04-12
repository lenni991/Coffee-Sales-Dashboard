# Coffee Sales Dashboard

### Overview
This repository contains the `OrdersData.xlsx` file, used to create an interactive dashboard for analyzing coffee sales data. The analysis was performed entirely in Excel, with data cleaning, consolidation, and visualization. The objective was to create a dashboard, allowing for easy filtering and exploration.

The dataset contains approximately **1200 rows** per sheet (Orders, Customers, and Products).


## Summary:

- Developed an interactive Excel dashboard analyzing $45,134 in coffee sales across 3 countries, leveraging advanced Excel functions to clean and consolidate 1,000+ records from multiple sheets with 14 data points per transaction.
- Created dynamic visualizations revealing 13% year-over-year growth (2019-2021), with United States generating 79% ($35,639) of total revenue and large packages (2.5kg) accounting for 53% ($23,786) of sales.
- Implemented 4 interactive filters enabling granular analysis across time periods, product attributes (4 coffee types, 3 roast types), and customer segments, identifying that March and June sales were 105% higher than lowest-performing month (August).


📁 **Project Files:**

```text
Coffee Sales Dashboard
├── Coffee_Sales_Data.xlsx     # Cleaned and consolidated dataset with the dashboard
└── OrdersData.xlsx            # Raw, uncleaned dataset
```
## Data Cleaning & Transformation

- **Data Cleaning:** Removed inconsistencies and missing values; standardized coffee and roast types.
- **Data Consolidation:** Merged customer details using `XLOOKUP` and product details using `INDEX MATCH` for analysis.
- **Calculations:** Created 'Sales' by multiplying 'Unit Price' and 'Quantity'.
- **Formatting:** Applied formatting to key columns like Order Date, Size, Unit Price, and Sales.

## Analysis & Visualization

- **Sales Over Time:** Pivot Table and Line Chart for sales trends by month/year.
- **Sales by Country:** Pivot Table and Bar Chart for sales by country.
- **Top Customers:** Pivot Table and Bar Chart for top 5 highest-spending customers.

## Interactivity Features

- **Timeline:** Interactive filter by 'Order Date'.
- **Slicers:** Filters for 'Roast Type', 'Size', and 'Loyalty Card'.
- **Custom Styling:** Applied cohesive styling to Timeline and Slicers.

## Result & Dashboard Features

A fully interactive dashboard providing insights into sales trends, top customers, and product performance. Allows filtering by time, roast type, size, and loyalty card usage.

![Dashboard Screenshot](https://github.com/user-attachments/assets/ffecb3e6-5dff-4f4a-991d-5d2727fe2bec)

- **Sales Over Time:** Coffee sales trends.
- **Sales by Country:** Revenue breakdown by country.
- **Top 5 Customers:** Highest-spending customers.
- **Filters:** Roast Types (Dark, Light, Medium), Package Sizes (0.2 kg to 2.5 kg), Loyalty Card usage.

## Key Insights

1. **Sales Distribution by Country:**
   - United States dominates with 79% of total sales ($35,638.89)
   - Ireland accounts for 15% ($6,696.87)
   - United Kingdom represents only 6% ($2,798.51)

2. **Yearly Sales Trends:**
   - 2021 was the peak year with $13,766.11 in sales
   - 2022 shows lower sales ($7,063.44).

3. **Seasonal Patterns:**
   - March and June show the highest monthly sales ($4,795.78 and $4,843.04)
   - August has the lowest sales ($2,326.90)
   - Strong Q1 and Q2 performance with weaker Q3 and Q4

4. **Product Performance:**
   - Excelsa coffee leads in sales ($12,306.44)
   - All coffee types show relatively balanced popularity, with Robusta slightly behind

5. **Package Size Preferences:**
   - Large packages (2.5kg) generate 53% of sales revenue ($23,785.57)
   - Smaller packages (0.2kg) account for only 7% of sales

6. **Customer Insights:**
   - Top 5 customers contribute $1,472.91 in sales
   - Customer loyalty is evenly distributed (479 customers with loyalty cards vs. 521 without)
   - Non-loyalty customers spend slightly more on average per order ($46.48 vs. $43.67)


