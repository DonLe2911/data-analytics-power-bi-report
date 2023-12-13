# Power BI Report - Milestone project for AICore course - General Store Dataset

## 1) 
Importing data into PowerBI from various sources:
- Azure SQL Database (Orders Table): Split order date and shipping date columns to sepearate date and time 
- CSV (Products table): removed duplicates. Split weight column into Value and Unit using column by example. Created calcualted column converting values in grams to kg.  
- Azure Blob Storage (Stores table)
- Zip file (Customers table): combined the numerous csv files. Created a full name column by merging first and last name columns 

## 2)
- Created Date table for time intelligence functions
- Built star schema model
- Created a number of key measures
- Created Date and Geography hierarchys

  ![2023-12-13 09_48_08-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/7e267d86-ae55-4e21-b6b8-7de695c014e2)

## 3)
- Created report pages and a nav side bar
- Created headline card visuals
- Created summary charts and tables:
    - Revenue per customer
    - Number of unique customers
    - Customers by country
    - Total customers over time, with forecast line
    - Top 20 customers showing total orders and total revenue for each
    - Total customers by category
- Added a date slicer

![2023-12-13 16_35_15-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/0d9eadb3-bc2c-4719-81b0-7f8b206f89fb)
