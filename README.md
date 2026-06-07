# Power-BI-Pedalworks-Business-Intelligence-Dashboard
Interactive Power BI Business Intelligence dashboard analysing sales, profitability, customer behaviour, product performance and returns. Built with DAX, data modelling, what-if analysis, bookmarks and dynamic reporting.

 🚴 PedalWorks Business Intelligence Dashboard

## Project Overview

This project showcases an end-to-end Business Intelligence solution developed in Power BI.

The objective was to transform raw sales, customer, product and returns data into meaningful business insights that support business decision-making.

The dashboard was designed for a fictional bicycle retailer, PedalWorks, to help management understand customer behaviour, product performance, profitability, returns and sales trends.

Rather than focusing only on reporting sales figures, this project aimed to uncover the customer groups driving business performance and identify opportunities for future growth.

## Business Problem

While analysing the sales data, I wanted to understand which customer segments generated the highest value for the business.

My initial hypothesis was that homeowners and customers with children may purchase more cycling-related products due to greater household spending power and family-oriented purchasing behaviour.

To investigate this, I developed an interactive Power BI dashboard to analyse customer demographics, product performance, sales trends and profitability.

The goal was to identify the customer groups that contributed most to revenue and determine how these insights could support future marketing and sales strategies.

## Project Objectives

- Analyse customer purchasing behaviour
- Identify high-value customer segments
- Monitor sales and profitability trends
- Evaluate product performance and return rates
- Analyse regional sales performance
- Support business decisions through interactive reporting
- Simulate pricing changes using What-If analysis

## Analytical Approach

The project began with a customer-focused question:

### Are homeowners and customers with children more valuable customers than other customer groups?

To answer this question, I analysed:

- Customer home ownership status
- Family and parental status
- Customer income levels
- Occupation categories
- Product purchasing behaviour
- Revenue contribution by customer segment

After identifying key customer patterns, I expanded the analysis to investigate product performance, return rates, profitability and regional sales performance to better understand the broader drivers of business success.

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Data Modelling
- Bookmarks
- Field Parameters
- What-If Parameters
- Interactive Visualisations

## Data Model

The solution uses a hybrid Star Schema and Snowflake Schema design.

### Fact Tables

- Sales Data
- Returns Data

### Dimension Tables

- Calendar Lookup
- Customer Lookup
- Territory Lookup
- Product Lookup

### Supporting Tables

- Product Category Lookup
- Product Subcategory Lookup
- Measure Table
- Product Metric Selection Parameter
- Price Adjustment Parameter

This structure improves reporting performance while maintaining clear business relationships between sales, customers, products and territories.

## Dashboard Pages

### Executive Dashboard

Provides a high-level overview of:

- Revenue
- Profit
- Orders
- Return Rate
- Revenue Trends
- Product Performance
- Return Analysis

### Territory Analysis

Visualises sales performance across regions and territories to identify top-performing markets.

### Product Analysis

Analyses:

- Product Revenue
- Product Profitability
- Return Rates
- Dynamic KPI Selection
- Price Adjustment Scenarios

### Customer Analysis

Explores:

- Customer Segmentation
- Income Groups
- Home Ownership Status
- Family Characteristics
- Customer Rankings

## Key Business Questions

### Customer Analysis

1. Which customer groups generate the highest revenue?
2. Do homeowners purchase more products than non-homeowners?
3. Do customers with children spend more than customers without children?
4. Which occupations generate the strongest sales performance?

### Product Analysis

5. Which products generate the highest revenue?
6. Which products generate the highest profit?
7. Which categories contribute the most orders?
8. Which products experience the highest return rates?

### Sales Analysis

9. How does revenue change throughout the year?
10. Which territories generate the strongest performance?
11. Are there seasonal sales patterns?

### Scenario Analysis

12. How would price increases affect revenue and profit?
13. Which products are most sensitive to pricing changes?

## Key Findings

### Customer Insights

The original hypothesis suggested that homeowners and customers with children may contribute a larger share of company revenue.

The analysis supported this assumption.

- Homeowners generated a larger share of total sales revenue compared to non-homeowners.
- Customers with children demonstrated stronger purchasing activity than customers without children.
- High-income households consistently contributed more revenue and profit.
- Professional and managerial occupations represented some of the most valuable customer segments.

These findings suggest that family households and financially established customers form a core customer base for the business.

### Product Insights

- Tires & Tubes was the highest-volume category, generating approximately 17,000 orders.
- A small number of products contributed a large proportion of total company revenue.
- Certain clothing products like shorts recorded higher return rates than core bicycle products.
- High-performing products delivered both strong revenue and profit margins.

### Sales Insights

- Total revenue reached approximately $24.9 million.
- Total profit exceeded $10.5 million.
- Revenue peaked at approximately $3.0 million in June before declining during the following months and recovering towards year-end.
- Several territories consistently outperformed others in both revenue and order volume.

### Pricing Insights

- What-If analysis demonstrated that moderate price increases improved profitability across several product groups.
- Higher-margin products delivered the strongest gains under simulated pricing scenarios.

## Business Story

The analysis began with a simple question:

### Who are the customers driving most of the business revenue?

By exploring customer demographics, I discovered that homeowners and customers with children represented some of the strongest-performing customer groups.

After identifying these customer segments, I expanded the investigation into product performance, profitability, returns and regional trends to understand what products were being purchased and where revenue was being generated.

The final dashboard provides management with a complete view of customer behaviour, product performance and business growth opportunities.

## Business Recommendations

### Customer Strategy

- Increase marketing efforts towards homeowners and family households.
- Develop targeted campaigns for high-income customer segments.
- Focus customer retention initiatives on the highest-value customer groups.

### Product Strategy

- Maintain strong inventory levels for top-performing categories such as Tires & Tubes.
- Investigate products with elevated return rates to reduce operational costs.
- Prioritise high-margin products within promotional campaigns.

### Revenue Growth

- Expand sales efforts in high-performing territories.
- Apply strategic pricing adjustments where profitability gains can be achieved without significantly impacting demand.

## Skills Demonstrated

- Data Modelling
- DAX Calculations
- Power Query
- Business Intelligence Reporting
- Dashboard Design
- Customer Segmentation
- Product Analytics
- What-If Analysis
- Field Parameters
- Interactive Reporting
- Data Storytelling
- Executive Reporting

## Project Outcome

This project demonstrates how Power BI can be used to transform operational data into actionable business insights.

Starting with a customer-focused hypothesis, the analysis evolved into a broader investigation of sales performance, product profitability, returns behaviour and regional trends.

The final solution enables management to monitor performance, identify growth opportunities, optimise product strategy and make data-driven decisions through interactive reporting.

## Repository Contents

### Data Model
- Hybrid Star and Snowflake Schema Design

### Video Demo
- Interactive Dashboard Demonstration

## Author

**Sudhanshu Singh**
Melbourne, Australia
