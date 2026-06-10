# KarmixTech_SupplyChainOperations_Dashboard

## Table of Contents
 - [Project Overview](#project-overview)
 - [Business Problem](#business-problem)
 - [Dataset](#dataset)
 - [Tools & Technologies Used](#tools--technologies-used)
 - [Data Preparation](#data-preparation)
 - [Dashboard Sections](#dashboard-sections)
 - [Key Insights](#key-insights)
 - [Business Impact](#business-impact)
 - [Recommendations](#recommendations)
 - [Dashboard Preview](#dashboard-preview)
 - [Conclusion](#conclusion)

## Project Overview

This project presents a Supply Chain & Operations Dashboard developed using Power BI and the DataCo Smart Supply Chain Dataset. The dashboard provides a comprehensive view of business performance, logistics efficiency, profitability, and delivery risk, enabling management to make data-driven decisions.

The goal of this project is to analyze supply chain operations and answer three key business questions:

  - What happened?
  - Why did it happen?
  - What action should be taken?

## Business Problem

Supply chain operations involve multiple challenges, including delivery delays, fluctuating profitability, and regional performance differences. Organizations need a centralized reporting solution to monitor operational efficiency and identify improvement opportunities.

This dashboard helps management:

  - Track revenue and profit performance
  - Monitor delivery risks
  - Analyze shipping efficiency
  - Identify high-performing products and markets
  - Support strategic decision-making

## Dataset

Dataset: [DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

## Tools & Technologies Used
  - Python	- Data Cleaning & Analysis
  - Matplotlib	- Data Visualization
  - Seaborn	- Exploratory Data Analysis
  - Microsoft Power BI	- Dashboard Development

## Data Preparation

The following preprocessing steps were performed:

### Data Cleaning
Removed missing values
Removed duplicate records
Converted date fields into datetime format
Removed unnecessary columns

### Feature Engineering

Created additional business metrics:

Average Delivery Time
Overall Profit Margin %
Late Delivery%
Order Month
Order Year
Order Month Name


## Dashboard Sections
#### 1. Executive KPI Overview

Provides a high-level summary of business performance.

Metrics included:

  - Total Revenue
  - Total Profit
  - Total Orders
  - Overall Profit Margin %
  - Late Delivery %
  - Average Delivery Time
#### 2. Monthly Revenue Trend

Analyzes monthly sales performance to identify seasonal patterns and revenue fluctuations.

Business Purpose:
  - Monitor sales trends
  - Identify peak and low-performing months
  - Support forecasting decisions
#### 3. Top 5 Products by Revenue

Highlights products generating the highest revenue.

Business Purpose:
  - Identify best-selling products
  - Support inventory planning
  - Optimize product strategy
#### 4. Profit by Market

Compares profitability across different markets.

Business Purpose:
  - Identify profitable regions
  - Support expansion strategies
  - Improve market-level performance
#### 5. Actual vs Scheduled Shipping Days

Compares planned shipping duration against actual delivery performance.

Business Purpose:
  - Measure logistics efficiency
  - Identify operational delays
  - Improve shipping performance
#### 6. Delivery Status Analysis

Analyzes delivery outcomes and delay risks.

Business Purpose:
  - Monitor service quality
  - Reduce delivery failures
  - Improve customer satisfaction

## Key Insights
  - Revenue Performance
    Revenue remains relatively stable throughout most months. A decline is observed during the final months of the year.
  - Product Performance
    A small number of products contribute a significant share of total revenue. Product sales are concentrated among top-performing items.
  - Market Performance
    Europe and LATAM generate the highest profit. Certain markets significantly outperform others in profitability.
  - Operational Efficiency
    Standard Class and Second Class shipping modes require the highest delivery time. Actual shipping days often exceed scheduled shipping days.
  - Delivery Risk
    More than half of the orders face late delivery risk. Delivery delays represent a major operational challenge.

## What Happened?

The analysis revealed:

  - Strong overall revenue generation ($36M+)
  - Healthy profit performance ($3.9M+)
  - Significant late delivery risk (54%+)
  - High dependence on a few top-selling products
  - Profit concentration in specific markets

## Why Did It Happen?

Several factors contribute to the observed performance:

  - Logistics Delays
    Actual shipping times exceed planned schedules.Standard and Second Class shipping modes show the highest delays.
  - Market Variations
    Some regions generate substantially higher profits than others.
  - Product Concentration
    Revenue relies heavily on a limited number of products.
  - Supply Chain Inefficiencies
    Delivery delays increase operational risk and impact customer experience.
## Business Impact

The identified issues may lead to:

  - Reduced customer satisfaction
  - Increased logistics costs
  - Higher operational risk
  - Lower supply chain efficiency
  - Potential revenue loss from delayed deliveries


## Recommendations
1. Optimize Shipping Operations

Improve Standard Class and Second Class shipping processes to reduce delays.

2. Improve Logistics Planning

Enhance route optimization and warehouse coordination to improve delivery performance.

3. Reduce Delivery Risk

Implement real-time shipment tracking and proactive delivery monitoring.

4. Focus on High-Profit Markets

Invest more resources in high-performing regions such as Europe and LATAM.

5. Strengthen Inventory Planning

Ensure adequate inventory levels for top-selling products to avoid supply disruptions.

6. Monitor Operational KPIs Regularly

Track delivery performance and shipping efficiency continuously to support proactive decision-making.

## Dashboard Preview

<img width="853" height="372" alt="image" src="https://github.com/user-attachments/assets/b2650ca8-3f8b-4a00-b4bb-c3ea794b6a00" />

## Conclusion

This Supply Chain & Operations Dashboard provides a comprehensive view of business performance, logistics efficiency, and delivery risk. By transforming raw supply chain data into actionable insights, the dashboard helps management identify operational bottlenecks, improve decision-making, and drive business growth.

The project demonstrates practical applications of Business Intelligence, Data Analytics, and Supply Chain Management using Python and Power BI.
