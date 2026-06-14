# World-Layoffs-Project-SQL
This project analyzes a global layoffs dataset containing workforce reduction events across companies, industries, countries, and funding stages. The objective was to perform end-to-end data cleaning and exploratory data analysis (EDA) using SQL to uncover patterns in layoffs and identify the organizations, sectors, and regions most affected over time.
The project demonstrates practical SQL skills including data cleaning, data transformation, window functions, Common Table Expressions (CTEs), joins, aggregations, and trend analysis.
# Key Insights and Features

• Identified companies with the highest total layoffs across the dataset.

• Analyzed layoffs by industry, country, funding stage, and year.

• Examined companies that laid off 100% of their workforce.

• Created monthly layoff trends and cumulative rolling totals.


• Ranked companies by annual layoffs using window functions.

• Standardized inconsistent values across company, industry, country, and date fields.

• Removed duplicate and incomplete records to improve data quality. 
# Why This Project Stands Out

• Demonstrates a complete SQL workflow from raw data cleaning to business-focused analysis.

• Utilizes advanced SQL concepts including ROW_NUMBER(), DENSE_RANK(), CTEs, joins, and window functions.

• Focuses on a real-world dataset involving global workforce trends and economic events.

• Generates actionable insights through structured exploratory analysis rather than simple descriptive queries.

• Highlights best practices in data preparation before conducting analysis.
# Project Highlights

1. Data Cleaning

• Removed duplicate records using ROW_NUMBER().

• Standardized company names, industries, countries, and date formats.

• Handled missing and null values through self-joins and updates.

• Eliminated records lacking meaningful layoff information.

2. Exploratory Data Analysis

• Company-wise layoff analysis.

• Industry and country impact assessment.

• Year-over-year layoff trends.

• Monthly rolling layoff calculations.

• Funding stage analysis.

• Top-ranked companies by layoffs for each year.

3. SQL Concepts Used

• Window Functions

• Common Table Expressions (CTEs)

• Aggregate Functions

•Joins

• Data Transformation

• Ranking Functions

• Data Cleaning Techniques
# Repository Structure
├── layoffs.csv # Original dataset

├── Data_Cleaning.sql # Data cleaning and transformation queries

├── Exploratory_Data_Analysis.sql # SQL queries used for analysis

└── README.md # Project documentation
