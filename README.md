# Power BI Report - Milestone project for AICore course - General Store Dataset

## 1) 
**Importing data into PowerBI from various sources**
- Azure SQL Database (Orders Table): Split order date and shipping date columns to sepearate date and time 
- CSV (Products table): removed duplicates. Split weight column into Value and Unit using column by example. Created calcualted column converting values in grams to kg.  
- Azure Blob Storage (Stores table)
- Zip file (Customers table): combined the numerous csv files. Created a full name column by merging first and last name columns 

## 2)
**Create data model**
- Created Date table for time intelligence functions
- Built star schema model
- Created a number of key measures
- Created Date and Geography hierarchys

  ![2023-12-13 09_48_08-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/7e267d86-ae55-4e21-b6b8-7de695c014e2)

## 3)
**Create customer detail report page**
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

## 4)
**Create executive summary report page**
- Copy over nav bar and date slicer
- Created summary charts and tables:
    - Cards for Total revenue, profit and order
    - Donut charts showing revenue per country and a second per store type
    - Bar chart of revenue by category
    - Revenue trend and forecast line chart
- Created KPI measures and card visuals for quarterly targets (Calculated at 5% more than previouis quarter values) for revenue, profit and orders
- Styling and themeing

![2023-12-14 14_56_16-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/a26bcb9d-3a83-4eff-9c96-5d4404ff8ab2)

## 5)
**Create Product Detail page**
- Gauges to track quarterly target progress on Orders, revenue and profit
- Area chart of revenue by category
- Top 10 products table by revenue
- Scatter graph to see whcih product ranges are both top seliing and profitable
- Created a slicer toolbar and using buittons/bookmarks make it appear and hidden as and when needed
- Created a card displaying most ordered product and product with most revenue

![2023-12-18 13_40_54-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/26164f33-a393-4119-87b2-3f3021f9d842)

![2023-12-18 13_41_10-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/9e512ca4-349a-4822-9252-fc06db28dfc5)

## 6)
**Creating a Stores map page**
- Add a mpa visual with bubbles representing Profit YTD
- Added a country slicer
- Created a drillthrough page enabling user to click on a country on the map and then click the drill through button to see individual store page detailing various useful sales/profits/orders info as well as target gauges, best performing categories and best performing products
- Creaetd a tooltip so that when hovering over a store on the map the profit target gauge will pop up

Map page: ![map](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/e883efd9-a231-4abc-a2c0-897acf2b9f89)

Image showing the tooltip pop up. Also note that as a country has been selected, the drill through button is now active:
![tooltip and drillthrough](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/2b0a185a-ec61-4c08-a985-2416cf0b9269)

The store drilltrhough page with a back button to get back to the map:
![2023-12-21 11_23_59-Power BI Report - AiCore](https://github.com/DonLe2911/data-analytics-power-bi-report/assets/16416867/a6018af2-e54e-443e-a5d4-5911d12f7c7b)




