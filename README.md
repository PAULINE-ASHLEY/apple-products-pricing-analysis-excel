# Apple Products Pricing & Market Analysis

An end-to-end Microsoft Excel data analysis project exploring Apple product pricing, discounts, customer satisfaction, stock availability, product condition, promotional events, platform performance, and price differences between the US and Indian markets.

## Project Overview

This project analyzes **80,000 Apple product listings** to identify patterns and trends in:

- Product pricing
- Discounts
- Customer ratings
- Customer reviews
- Stock availability
- Product condition
- Platform performance
- Promotional events
- US–India price differences

The project demonstrates a complete data analysis workflow using Microsoft Excel:

**Raw Data → Data Cleaning → KPI Analysis → PivotTables → Data Visualization → Interactive Dashboard → Business Insights**

## Business Questions

This analysis seeks to answer the following questions:

- Which Apple product categories have the highest and lowest average prices?
- How do US and India prices compare after currency conversion?
- Which market offers higher average discounts?
- Which product categories receive the highest discounts?
- How do Amazon and Flipkart compare in pricing and customer performance?
- Which promotional events are associated with the highest discounts?
- Which product categories have the highest stock availability and stock-out levels?
- How do new products compare with renewed/refurbished products?
- How does the percentage price difference vary between the US and Indian markets?

## Dataset

The dataset contains **80,000 Apple product listings** with information including:

- Date
- Platform
- Product category
- Model name
- Product condition
- Launch price in USD
- Launch price in INR
- Current price in USD
- Current price in INR
- Current India price converted to USD equivalent
- Current price difference
- Current price percentage difference
- US discount percentage
- India discount percentage
- Sale event
- Stock status
- Customer rating
- Review count
- Year
- Month

## Tools Used

- **Microsoft Excel**
- Excel Tables
- Excel formulas
- Data cleaning
- KPI development
- PivotTables
- PivotTable-connected slicers
- Charts and data visualization
- Interactive dashboard
- Currency conversion
- Comparative market analysis

## Data Analysis Process

### 1. Data Preparation and Cleaning

The raw dataset was reviewed and prepared for analysis.

Additional calculated fields were used to support the analysis, including:

- Current India price in USD equivalent
- Current US–India price difference
- Current US–India price percentage difference
- US discount percentage
- India discount percentage
- Year
- Month

Indian prices were converted to USD equivalents using an exchange rate of:

**96.2537 INR per USD**

**Exchange Rate Date:** 21 July 2026

### 2. KPI Analysis

Key performance indicators were created to provide a high-level overview of the dataset.

The main KPIs include:

- Total product listings
- Average US current price
- Average India current price in USD equivalent
- Average US discount
- Average India discount
- Average customer rating
- Total customer reviews
- In-stock rate

### 3. PivotTable Analysis

The following PivotTables were created:

#### Product Category Performance

Analyzes:

- Average US current price
- Average India current price
- Average rating
- Total reviews
- Total stock
- Average US discount
- Average India discount

#### Platform Performance

Compares Amazon and Flipkart across:

- Average price
- Average US discount
- Average India discount
- Total stock
- Average rating
- Average reviews

#### Sale Event Performance

Analyzes:

- Average US current price
- Average India current price
- Number of products
- Average US discount
- Average India discount

The analysis includes:

- Big Billion Days
- Black Friday
- Great Indian Festival
- Prime Day
- Products without a recorded sale event

#### Stock Analysis

Examines the number of products that are:

- In Stock
- Low Stock
- Out of Stock

Across different product categories.

#### Product Condition Analysis

Compares:

- New
- Renewed/Refurbished

Across:

- Average US price
- Average India price
- Average US discount
- Average India discount
- Average customer rating

#### US–India Price Comparison

Compares:

- Average US current price
- Average India current price converted to USD
- Percentage price difference between the two markets

## Dashboard

An interactive Excel dashboard was created using:

- KPI cards
- Charts
- PivotTables
- Connected slicers

The dashboard allows users to interactively filter the analysis by dimensions such as:

- Product category
- Platform
- Product condition
- Stock status
- Sale event

## Key Findings

### Product Category Pricing

Mac products have the highest average US current price at approximately **1,382.49**.

Watches have the lowest average US current price at approximately **398.64**.

### Market Pricing

The average US current price is approximately **782.77**, compared with approximately **775.33** for the India price converted to USD.

The US average price is therefore approximately **7.44 higher**.

### Discounts by Market

The average US discount is approximately **21.42%**.

The average India discount is approximately **23.55%**.

This indicates that the average India discount is approximately **2.13 percentage points higher** than the average US discount.

### Product Category Discounts

Watches and iPads receive the highest average US discounts:

- Watch: **26.27%**
- iPad: **26.19%**

Mac products receive the lowest average US discount at approximately **15.43%**.

India discounts are higher across all four analyzed product categories.

### Platform Performance

Amazon and Flipkart perform very similarly.

Amazon has:

- Average US discount: **21.52%**
- Average India discount: **23.65%**
- Average rating: **4.45**

Flipkart has:

- Average US discount: **21.32%**
- Average India discount: **23.46%**
- Average rating: **4.45**

The differences between the platforms are relatively small.

### Promotional Events

Big Billion Days records the highest average discounts:

- US discount: **37.02%**
- India discount: **38.72%**

This is followed by:

- Prime Day
- Great Indian Festival
- Black Friday

Products without a recorded sale event have significantly lower average discounts.

### Inventory

The overall in-stock rate is approximately **68.79%**.

iPhones have the highest number of products in stock at **19,932**.

They also have the highest absolute number of out-of-stock products at **4,670**.

Because iPhones have the largest number of listings, stock performance should be evaluated using both absolute counts and percentages.

### Product Condition

New products have a higher average US current price of approximately **830.07**, compared with **641.02** for renewed/refurbished products.

New products also have a higher average rating:

- New: **4.55**
- Renewed/Refurbished: **4.15**

Renewed/refurbished products receive substantially higher discounts:

- Average US discount: **35.53%**
- Average India discount: **44.10%**

### US–India Price Percentage Difference

The US current price is higher than the India USD-equivalent price across all analyzed product categories.

The percentage difference ranges from approximately **1.49% to 1.61%**, depending on the product category.

Mac products show a percentage difference of approximately **1.59%**, while Watches show the largest difference at approximately **1.61%**.

## Business Recommendations

### Inventory Management

The business should monitor categories with high stock-out levels and evaluate inventory using both total counts and stock percentages.

### Promotional Strategy

Major promotional events are associated with significantly higher discounts. Businesses should evaluate whether increased sales volume during these events justifies the reduction in profit margins.

### Renewed and Refurbished Products

Renewed/refurbished products offer significantly higher discounts but have lower average customer ratings than new products.

Businesses should focus on quality control, refurbishment standards, warranties, and customer service in this segment.

### Category-Specific Pricing

Mac products command the highest average prices and receive the lowest average discounts. This suggests that premium products may have stronger pricing power.

### Market Pricing

The US and India markets show relatively similar prices after currency conversion. Further analysis involving taxes, import duties, shipping costs, distribution expenses, and purchasing power could provide additional explanations for the remaining differences.

## Project Files

- `apple-products-pricing-analysis-excel.xlsx` — Complete Excel analysis workbook
- `dashboard.png` — Screenshot of the interactive Excel dashboard

## Skills Demonstrated

- Data cleaning
- Excel formulas
- KPI development
- PivotTable analysis
- Data visualization
- Dashboard development
- Interactive slicers
- Currency conversion
- Market comparison
- Business insight generation
- Data-driven recommendations

## Author

**Pauline Ondiek**
