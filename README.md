# Supply Chain Performance

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Tools Used](#tools-used)
- [Methodology](#methodology)
- [Research Questions](#research-questions)
- [Processes](#processes)
- [Insights](#insights)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)

## Introduction
Supply chains are the backbone of product driven businesses. Efficient cost management, defect tracking and stock optimization are essential for maintaining profitability and customer satisfaction.
This project presents an interactive Power BI dashboard that analyzes the supply chain performance of three product categories skincare, haircare and cosmetics across various shipping carriers and transport modes. The dashboard is designed to provide real time insights for decision makers managing costs, quality and logistics.

![Screenshot (484)](https://github.com/user-attachments/assets/a9e28d2d-166e-4ec2-a26b-79ea11dd3754)


## Objective
The goal of this analysis is to:
- Visualize supply chain performance across key operational metrics
- Identify high performing and underperforming products, carriers and transport methods
- Track stock levels, revenue contributions, cost distribution and defect rates
- Enable data driven decision making to improve supply chain efficiency

## Dataset Overview
The dataset consists of key operational and sales data from a retail supply chain system. Fields include:
- Product Type (Skincare, Haircare, Cosmetics)
- SKU identifiers
- Total Cost
- Revenue Generated
- Price per Unit
- Stock Levels
- Defect Counts and Rates
- Shipping Carrier (A, B, C)
- Transport Mode (Air, Rail, Road, Sea)
- Shipping and Transport Cost

## Tools Used
- Power BI Desktop: Data import, modeling, DAX calculations, interactive visualizations and dashboard creation

## Methodology
1. Data Preparation
   - Cleaned and standardized product types, transport modes and carrier names
   - Calculated derived metrics: total cost, average transport cost, total and average defect rates

2. Data Modeling in Power BI
   - Related product type, SKU and logistics dimensions using a star schema
   - Created calculated measures (e.g. total revenue, defect rate by category and mode)

3. Dashboard Development
   - Visualized KPIs (No. of Products, Total Revenue, Defect Rate, Avg. Transport Cost)
   - Added slicers for Transportation Mode and Product Type for interactive filtering
   - Built intuitive visual layouts for comparisons across cost, revenue, stock and quality metrics

## Research Questions
- Which product types generate the most revenue and incur the highest costs?
- How does shipping cost vary by carrier and transport mode?
- What’s the average defect rate by product and shipping method?
- How are stock levels distributed across SKUs?
- What’s the cost-to-revenue relationship across product categories?

## Processes
### Data Modeling
- Connected data tables (products, shipping, defect logs) in Power BI
- Created DAX measures:
  - Total Cost, Total Revenue, Average Defect Rate, Shipping Cost %

### Visualizations Created
- KPI Cards: High level indicators for product count, costs and defect rates
- Bar Charts:
  - Product Price vs. Revenue by Category
  - Revenue by Carrier
  - Defect Rates by Product and Transport Mode
- Pie Charts:
  - % Sales by Product Type
  - Shipping Cost by Carrier
- Line Chart:
  - Stock Levels by SKU
- Column Chart:
  - Transport Mode Cost Comparison

### Interactivity
- Added slicers for:
  - Product Type
  - Transportation Mode
- Enabled cross filtering between visuals for exploratory analysis

## Insights
### Revenue vs Cost Analysis
- Skincare leads in total revenue generated (₦0.24M) followed by Haircare (₦0.17M) and Cosmetics (₦0.16M)
- Despite higher revenue skincare also contributes a higher share of defects and transport cost suggesting room for process improvement

### Carrier Performance
- Carrier B is responsible for the highest revenue (₦250.09K) and also the highest shipping cost share (42.7%)
- Carrier A is the most cost-efficient but generates the lowest revenue

### Transport Mode Cost Breakdown
- Road transport is the most expensive mode overall (₦16K) followed by rail and air
- Sea transport is the most cost efficient (₦7.1K) but has variable defect implications depending on the product

### Quality Control
- Haircare shipped by air has the highest average defect rate (3.64)
- Cosmetics transported by sea show the lowest defect rate (0.40) indicating potential for greater use of sea freight for this product

### Inventory Trends
- Stock levels for most SKUs remain high (90+ units) but some products (e.g. SKU54, SKU51) are nearing low stock and may require restocking soon

## Key Findings
- Skincare is the highest-revenue but also highest-defect product line opportunities exist to improve quality control
- Carrier B is effective in revenue delivery but expensive worth auditing for optimization
- Sea transport is most cost effective and offers lower defect rates for certain products
- Haircare via air needs immediate review due to defect risks
- SKU-level stock depletion flags inventory gaps that should be addressed

## Conclusion
This supply chain dashboard offers clear visibility into the core performance metrics driving logistics, product quality and profitability. By combining revenue, cost, defect and inventory views the dashboard allows operations and supply chain teams to make quick data-informed decisions. Future iterations could integrate supplier level performance, lead times and predictive alerts for low stock or rising defect trends.
