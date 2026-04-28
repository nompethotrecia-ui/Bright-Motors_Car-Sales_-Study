# Car Sales Analysis – Bright Motors

## Project Overview

This project is a Business Analytics case study completed for BrightLearn, focused on analyzing the **Bright Car Sales** dataset for Bright Motors.

As a **Junior Data Analyst**, the objective was to provide data-driven insights to support the newly appointed Head of Sales in improving dealership performance, optimizing inventory, and increasing profitability.

The project combines **SQL, data cleaning, data transformation, dashboard creation, and business recommendations** to solve real-world sales challenges.


## Business Problem

Bright Motors recently appointed a new Head of Sales whose mission is to:

- Expand dealership networks
- Improve sales performance
- Optimize inventory management
- Increase dealership profitability
- Understand customer purchasing trends

This analysis helps identify opportunities and provides strategic recommendations based on historical car sales data.


## Objectives

The analysis focuses on answering the following key business questions:

- Which car makes and models generate the most revenue?
- What is the relationship between price, mileage, and year of manufacture?
- Which regions or locations have the highest sales volumes?
- What are the emerging trends in customer purchasing preferences?
- What recommendations can improve profitability and efficiency?


## Tools Used

### SQL & Data Processing
- Snowflake
- Google BigQuery
- Microsoft SQL Server

### Data Visualization
- Microsoft Excel
- Power BI
- Google Looker Studio

### Presentation & Planning
- Microsoft PowerPoint
- Canva


## Project Tasks

### Task 1: Planning & Architecture

Created a data flow architecture showing:

- Source Layer → Car Sales CSV/Excel Dataset
- ETL Pipeline → Data cleaning and transformation
- Storage Layer → SQL Database (Snowflake)
- Analysis Layer → SQL + Power BI / Excel
- Presentation Layer → Final Business Presentation

Key insights planned:

- Revenue by make and model
- Sales distribution by year and fuel type
- Regional sales performance
- Average selling price trends


### Task 2: Data Processing in SQL

Performed:

- CSV conversion and database loading
- Data cleaning
- Removing duplicates
- Handling missing values
- Converting text prices to numeric values
- Creating calculated fields:
  - `total_revenue`
  - `profit_margin`
- Categorizing performance tiers:
  - High Margin
  - Medium Margin
  - Low Margin
- Time-based grouping:
  - Monthly
  - Quarterly
  - Yearly

### Task 3: Data Analysis & Dashboarding

Built interactive dashboards using:

- Excel
- Power BI

Features included:

- Region slicers
- Fuel type filters
- Year filters
- Revenue visuals
- Trend analysis
- Regional comparisons
- Pricing insights


### Task 4: Executive Presentation

Created a professional presentation for the Head of Sales summarizing:

- Key findings
- Business recommendations
- Profitability improvement strategies
- Sales optimization opportunities


## Key Calculations

### Total Revenue

```sql
total_revenue = selling_price * units_sold
