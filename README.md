# Mobile Sales Analytics Dashboard | Power BI

An interactive multi-page Power BI dashboard designed to monitor and analyze mobile phone retail sales, customer demographics, channel performance, state-level distribution, brand market share, and specific product model deep-dives.

**Created by:** Sathiyamoorthi S  
**Tool:** Microsoft Power BI  
**Reporting Period:** Multi-Year Mobile Retail Data  
**Domain:** Sales Analytics | Product & Brand Intelligence | Customer & Regional Analytics

## Dashboard Preview

[![Mobile Sales Analytics Dashboard](Screenshots/mobile-sales-analytics-overview.png)](https://github.com/Sathiyamoorthi-DA/Mobile-Sales-Analytics-Dashboard-Power-BI/blob/main/Screenshots/Mobile_sales_analysis_overview.png)

[![Mobile Sales Analytics Dashboard](Screenshots/mobile-sales-analytics-overview.png)](https://github.com/Sathiyamoorthi-DA/Mobile-Sales-Analytics-Dashboard-Power-BI/blob/main/Screenshots/Mobile_sales_Product%26Brand%20Dashbaord.png)

## Business Objective

The objective of this project is to build an enterprise-level sales and product analytics solution that gives executive stakeholders full visibility into overall revenue performance, brand market share, customer demographics, regional geographic demand, sales channel efficiency, and detailed model-level granular metrics.

## Key Performance Indicators

### Overall Portfolio Metrics
- **Total Revenue:** ₹444.8M *(▲ +56.7% vs. Last Year)*
- **Units Sold:** 8,598 *(▲ +56.6% vs. Last Year)*
- **Total Customers:** 1,686 *(▲ +13.2% vs. Last Year)*
- **Total Transactions:** 5,000
- **Average Selling Price (ASP):** ₹51.74K *(▲ 0.0% vs. Last Year)*
- **Average Customer Rating:** 4.2 / 5.0
- **Return Rate:** 6.2%

### Single Product Deep-Dive (e.g., Apple iPhone 15)
- **Total Revenue:** ₹13.6M
- **Total Units Sold:** 209
- **Average Selling Price (ASP):** ₹64.89K
- **Average Customer Rating:** 4.2 / 5.0

*Note: These values are captured directly from the report screenshots and should be validated against the underlying dataset.*

## Dashboard Pages & Features

### 1. Executive Sales Overview
- **Revenue & Unit Trends:** Tracks monthly sales trajectories and growth variations across the calendar year.
- **Brand Market Share:** Revenue breakdown across top smartphone manufacturers led by Apple (₹86M), Google (₹69M), Samsung (₹68M), Vivo (₹38M), and Oppo (₹38M).
- **Sales Channel Analysis:** Revenue distribution across Marketplace (26%), Retail Stores (25%), Dealers (25%), and Online (24%).
- **Geographic & Top State Ranking:** Regional heat maps and top state performance led by Gujarat (₹58.2M, 1,098 units), Maharashtra (₹52.5M, 1,010 units), and Tamil Nadu (₹29.8M, 598 units).
- **Top Cities by Revenue:** Detailed table of city-level sales including Ahmedabad (₹30.3M), Chennai (₹29.8M), Kolkata (₹29.6M), and Chandigarh (₹29.4M).

### 2. Product & Brand Analysis
- **Brand Revenue vs. Volume:** Multi-metric comparison mapping total units sold against total revenue generated per brand.
- **Top Models by Volume:** Identifies top-selling smartphone models like Oppo F-Series (331 units), Pixel 9 (323 units), Moto G-Series (314 units), and Vivo X100 (306 units).
- **Average Selling Price (ASP) Comparison:** Evaluates brand positioning ranging from premium brands like Apple (₹97K ASP) and Google (₹77K ASP) down to budget/mid-range brands like Realme (₹30K ASP).
- **Brand Revenue Contribution:** Donut chart breakdown showing market share (Apple 29%, Google 23%, Samsung 23%, Vivo 13%, Oppo 13%).

### 3. Customer & Regional Intelligence
- **Demographics & Age Groups:** Analyzes buyer distribution showing dominant adoption among 18–24 year olds (45.14%) and 25–34 year olds (26.33%).
- **Gender Share:** Customer split across Female (64%), Male (26%), and Other (10%).
- **Ratings & Transactions:** Transaction distribution mapped against customer rating scores.
- **Payment Method Preference:** Sales distribution across UPI (21%), Cash (20%), Credit Card (20%), EMI (20%), and Debit Card (19%).
- **Regional Matrix Table:** Summary metrics across East, North, South, and West sales zones.

### 4. Product Performance Details (Model Drill-Down)
- **Granular Filter View:** Filter down to specific brands and models (e.g., Apple iPhone 15).
- **Channel Unit Breakdown:** Highlights units sold via Online (56), Marketplace (55), Retail Store (52), and Dealer (46).
- **State-Level Revenue for Selected Model:** Top revenue states for the specific model led by West Bengal (₹1.6M) and Maharashtra (₹1.6M).
- **Transaction Log Table:** Detailed line-item breakdown showing sale dates, city, channel, payment method, quantity, revenue, and individual ratings.

## Business Questions Addressed

- Which mobile brands generate the highest revenue and unit sales?
- How is revenue distributed across online, marketplace, retail, and dealer channels?
- What are the top-performing states and cities driving total sales volume?
- Which demographic age groups and customer genders constitute the primary target market?
- How do payment preferences (UPI, Credit Card, EMI, Cash) compare among buyers?
- How does a specific smartphone model perform across individual channels and states?

## Tools and Skills

- Microsoft Power BI
- Data Analysis Expressions (DAX)
- Data Modeling & Star Schema Architecture
- Multi-Page Navigation & Executive UI Design
- Dynamic Slicers & Page Interactions
- Regional & Demographic Segmentation
- Drill-Through & Detailed Data Tables

## How to Explore the Dashboard

Download the Power BI report file (.pbix) from the repository.

Open the file in Microsoft Power BI Desktop.

Update data source connection paths if required.

Click Refresh to load the data model.

Navigate through the left sidebar icons (Home, Sales, Customer) or use the top drop-down slicers (Year, Region, Channel, Brand, Model) to filter insights.

## Author
Sathiyamoorthi S

Portfolio Project: Mobile Sales Analytics Dashboard

Focus: Retail Analytics | Power BI | Business Intelligence | Customer Insights

## Project Structure

```text
Mobile-Sales-Analytics-PowerBI/
├── README.md
├── Screenshots/
│   ├── mobile-sales-analytics-overview.png
│   ├── product-and-brand-analysis.png
│   ├── customer-and-regional-intelligence.png
│   └── product-performance-details.png
├── data/
│   └── mobile_sales_dataset.csv
├── powerbi/
│   └── Mobile_Sales_Analytics.pbix
└── DAX_Measures.md
