# Sales Overview Analysis – Power BI Dashboard
## Project Overview

This project presents an interactive Power BI dashboard designed to analyze and visualize sales performance across different regions. The dashboard enables users to explore key business metrics such as Sales, Profit, and Quantity, and compare current year performance with previous year results.

The goal of this project is to demonstrate how business intelligence tools like Power BI can transform raw data into meaningful insights that support data-driven decision-making.

This project covers the complete data analytics workflow including data preparation, data modeling, DAX calculations, and dashboard visualization.

Business Problem

Businesses need a clear understanding of how their sales are performing across different regions and time periods.

This dashboard helps answer important business questions such as:

Which region generates the highest sales?

How has sales performance changed compared to the previous year?

Which states contribute the most to overall revenue?

What are the trends in sales, profit, and quantity over time?

How do different regions compare in terms of performance?

The dashboard provides a dynamic and interactive view of sales data, enabling users to filter results and quickly identify key trends.

## Dataset

The dataset used for this project contains information about:

Order Date

Region

State

Sales

Profit

Quantity

Product details

This dataset simulates a typical retail or e-commerce sales dataset used for business analysis.

Project Workflow

The project follows a structured data analytics workflow:

1. Requirement Gathering

Understanding business needs and defining the key performance indicators (KPIs) required for the dashboard.

2. Data Walkthrough

Reviewing the dataset structure, identifying columns, and understanding the relationships between different data fields.

3. Data Connection

Importing the dataset into Power BI for analysis.

4. Data Cleaning and Quality Check

Using Power Query Editor to prepare the data by:

Removing duplicates

Fixing incorrect data types

Handling missing values

Renaming columns

Preparing the dataset for modeling

5. Data Modeling

Creating relationships between tables to support efficient analysis.

A star schema model was used to organize the data effectively.

6. Data Processing

Transforming the data to make it suitable for reporting and analysis.

7. DAX Calculations

Creating calculated measures to analyze performance metrics.

Key DAX measures include:

Current Year Sales

Previous Year Sales

Year-over-Year Growth

Profit and Quantity comparisons

8. Dashboard Layout Design

Designing a user-friendly layout that makes the dashboard easy to understand and visually appealing.

9. Charts Development

Creating different types of visualizations to present insights clearly.

10. Insights Generation

Extracting meaningful insights from the data to support business decisions.

Key Features of the Dashboard
KPI Metrics

The dashboard tracks three main performance indicators:

Sales

Profit

Quantity

Users can dynamically switch between these metrics.

Regional Performance Analysis

The dashboard analyzes performance across four regions:

Central

East

South

West

Each region displays:

Current Year Performance

Previous Year Comparison

Monthly Sales Trend

Dynamic Metric Selection

Users can switch between:

Sales

Profit

Quantity

This allows flexible analysis without changing the dashboard structure.

Sales Trend Analysis

Monthly trends are visualized using charts that help identify:

Seasonal patterns

Sales fluctuations

Overall growth trends

Sales Distribution by State

A bubble map visualization is used to show the distribution of sales across different states.

Bubble size represents sales volume, allowing quick identification of high-performing regions.

## State-Level Comparison

A bar chart visualization provides a detailed breakdown of sales by state, making it easier to compare performance across locations.

Performance Comparison Table

The dashboard includes a table that compares key metrics between current and previous years.

Metrics included:

Current Year Sales

Previous Year Sales

Year-over-Year Sales Growth

Current Year Profit

Previous Year Profit

Year-over-Year Profit Growth

Current Year Quantity

Previous Year Quantity

Year-over-Year Quantity Growth

## Tools and Technologies Used

Power BI
Power Query
DAX (Data Analysis Expressions)
