# Coffee Sales Dashboard

### Overview

This repository contains the `OrdersData.xlsx` file, which was used to create a dashboard for analyzing coffee sales `coffeeOrderDate`. All data cleaning and analysis were performed entirely in Excel, using features like **XLOOKUP()** to consolidate data from multiple sheets into the `Orders` sheet for streamlined analysis.
The objective was to analyze coffee sales data by creating an interactive dashboard featuring key metrics and visualizations, allowing for easy filtering and exploration of the data.

📁 Project Files

```text
Coffee Sales Dashboard
├── Coffee_Sales_Data.xlsx     # Cleaned and consolidated dataset with the dashboard
└── OrdersData.xlsx            # Raw, uncleaned dataset
```


## Data Source & Transformation

1.  **Data Gathering:** I started with three separate data sheets: Orders, Customers, and Products.
2.  **Data Consolidation:**
    * I used `XLOOKUP` to bring customer details (Name, Email, Country) into the main Orders table based on Customer ID.
    * I used `INDEX MATCH` to add product information (Coffee Type, Roast Type, Size, Unit Price) to the Orders table based on Product ID.
3.  **Calculations:**
    * I calculated the 'Sales' amount for each order by multiplying 'Unit Price' and 'Quantity'.
4.  **Data Cleaning & Formatting:**
    * I used `IF` functions to convert abbreviated coffee and roast types into their full names for clarity.
    * I applied appropriate formatting to columns like Order Date, Size, Unit Price, and Sales.
5.  **Added Loyalty Data:** I added a 'Loyalty Card' column using `XLOOKUP` based on Customer ID and refreshed the data [00:36:52, 00:38:47].

## Analysis & Visualization (Pivot Tables & Charts)

1.  **Sales Over Time:**
    * I inserted a **Pivot Table** from the "orders table"
    * I created a Line Chart showing total sales, grouped by month and year.
    * I customized the chart's appearance (colors, title, labels).
2.  **Sales by Country:**
    * I created a Pivot Table and generated a Bar Chart showing total sales per country.
3.  **Top Customers:**
    * I created a Pivot Table and generated a Bar Chart displaying the top 5 customers based on their total sales.

## Interactivity Features

1.  **Timeline:** I inserted an interactive Timeline linked to the 'Order Date' field, allowing filtering by specific date ranges
2.  **Slicers:** I added Slicers for 'Roast Type', 'Size', and 'Loyalty Card' to enable easy filtering of the data across all charts.
3.  **Custom Styling:** I created and applied custom visual styles to the Timeline and Slicers for a cohesive look.

#### Dashboard Features

- **Total Sales Over Time**: Sales trends for coffee varieties (Arabica, Excelsa, etc.).
- **Sales by Country**: Breakdown of revenue from top countries (e.g., US, Ireland).
- **Top 5 Customers**: Highlight of the highest-spending customers.
- **Interactive Filters**:
  - Roast Types: Dark, Light, Medium.
  - Package Sizes: 0.2 kg to 2.5 kg.
  - Loyalty Card usage.

## Result
![image](https://github.com/user-attachments/assets/ffecb3e6-5dff-4f4a-991d-5d2727fe2bec)



The final result is a fully interactive Excel dashboard that provides insights into coffee sales trends, geographical performance, top customers, and product details, which can be dynamically filtered by time period, roast type, size, and loyalty status.

