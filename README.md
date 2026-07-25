# Apple Products Pricing & Market Analysis

An interactive Microsoft Excel data analysis project exploring Apple product pricing, discounts, customer ratings, reviews, stock availability, product condition, platform performance, and US–India market price differences.

## Project Overview

This project analyzes a dataset containing approximately **80,000 Apple product listings** to identify patterns in product pricing, discounts, customer satisfaction, stock availability, and market differences.

The project demonstrates an end-to-end data analysis workflow using Microsoft Excel:

**Raw Data → Data Cleaning → KPI Analysis → PivotTables → Data Visualization → Interactive Dashboard → Business Insights**

## Business Questions

The analysis seeks to answer the following questions:

- Which product categories have the highest and lowest average prices?
- Which product categories receive the largest discounts?
- Which platform offers the highest average discount?
- Which product categories have the highest customer ratings?
- Which sale events are associated with the highest discounts?
- Which product categories have the highest stock availability and stock-out levels?
- How do new products compare with renewed or refurbished products?
- How do US prices compare with India prices after currency conversion?

## Tools Used

- **Microsoft Excel**
- Excel Tables
- Excel formulas
- PivotTables
- PivotTable-connected slicers
- Charts and data visualization
- Interactive dashboard
- Currency conversion analysis

## Analysis Process

### 1. Data Preparation

The dataset was reviewed and prepared for analysis. Relevant fields included:

- Product category
- Platform
- Product condition
- Sale event
- Stock status
- Current price in USD
- Current price in INR
- Launch price in USD
- Launch price in INR
- Customer rating
- Review count

### 2. KPI Analysis

Key performance indicators were created to provide a high-level overview of the dataset, including:

- Total product listings
- Average current price
- Average discount
- Average customer rating
- Total reviews
- In-stock rate

### 3. PivotTable Analysis

Several PivotTables were created to analyze:

- Product category performance
- Platform performance
- Sale event performance
- Stock availability
- Product condition
- US–India price comparison

### 4. Data Visualization

The analysis was visualized using Excel charts, including:

- Average customer rating by product category
- Average discount by platform
- Average discount by sale event
- Stock availability by product category
- Average price by product condition
- US vs India average price comparison

### 5. Interactive Dashboard

An interactive Excel dashboard was created using:

- KPI cards
- Charts
- Slicers
- Connected PivotTables

The dashboard allows users to filter the analysis by dimensions such as:

- Product category
- Platform
- Stock status
- Product condition
- Sale event

## Key Findings

### Pricing

Mac products have the highest average US current price at approximately **1,382.49**, while Watches have the lowest average price at approximately **398.64**.

### Discounts

Watches and iPads have the highest average discounts at approximately **26.27%** and **26.19%**, respectively. Mac products have the lowest average discount at approximately **15.43%**.

### Platform Performance

Amazon has a slightly higher average discount than Flipkart, at approximately **21.52%** compared with **21.32%**. Average customer ratings are nearly identical across both platforms.

### Promotional Events

Big Billion Days records the highest average discount at approximately **37.02%**, followed by Prime Day at **34.44%** and the Great Indian Festival at **33.45%**.

Products without a recorded sale event have a significantly lower average discount of approximately **20.30%**.

### Inventory

iPhones have the highest number of products in stock, with approximately **19,932 listings**. They also have the highest absolute number of out-of-stock listings, with approximately **4,670 listings**.

The overall in-stock rate is approximately **68.79%**.

### Product Condition

New products have a higher average US current price of approximately **830.07**, compared with **641.02** for renewed or refurbished products.

New products also have a higher average customer rating of approximately **4.55**, compared with **4.15** for renewed or refurbished products.

Renewed or refurbished products receive significantly higher average discounts of approximately **35.53%**, compared with **16.71%** for new products.

### US vs India Price Comparison

After converting Indian prices to USD equivalents, US prices are slightly higher across the analyzed product categories.

Mac products show the largest absolute difference, with US prices approximately **13.54 higher** than the India USD equivalent.

The percentage difference between the two markets remains relatively small, ranging from approximately **1.49% to 1.61%** across the analyzed categories.

**Exchange Rate Assumption:** Indian prices were converted using an exchange rate of **96.2537 INR per USD**.

## Business Recommendations

### Inventory Management

Inventory teams should closely monitor product categories with high stock-out levels. Stock-out performance should be evaluated using both absolute counts and percentages to account for differences in category size.

### Promotional Strategy

Businesses should evaluate major promotional events such as Big Billion Days and Prime Day because these events are associated with significantly higher average discounts.

### Renewed and Refurbished Products

Renewed and refurbished products offer significantly higher discounts and may appeal to price-sensitive customers. However, their lower average customer ratings suggest that product quality and customer experience should be monitored.

### Premium Product Pricing

Mac products maintain the highest average prices while receiving the lowest average discounts. This suggests that premium products may have stronger pricing power and require less aggressive discounting.

### Market Pricing

US and India prices are relatively similar after currency conversion. Further analysis incorporating taxes, shipping costs, import duties, and purchasing power could provide additional insight into regional price differences.

## Dashboard Preview

![Apple Products Analysis Dashboard](dashboard.png)

## Project Files

- `Apple Products.xlsx` — Complete Excel analysis workbook
- `dashboard.png` — Screenshot of the interactive dashboard

## Skills Demonstrated

- Data cleaning and preparation
- Excel formulas
- KPI development
- PivotTable analysis
- Data visualization
- Dashboard development
- Slicer-based interactivity
- Currency conversion
- Comparative market analysis
- Business insight generation
- Data-driven recommendations

## Author

**Pauline Ondiek**
