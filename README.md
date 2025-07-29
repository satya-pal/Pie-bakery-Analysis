# Pie Bakery Analysis Report
# Project Overview
This analysis is based on transactional data from a pie bakery, spanning the years 2019 to 2022. The primary objective is to understand sales trends, customer behavior, and revenue patterns to derive actionable insights for the business.

# Objectives of the Analysis
The following questions were addressed in this project:
How many items are sold per Year, Quarter, and Month?
What is the comparison of total orders across weekdays?
What is the total revenue earned by Quarters?
What is the distribution of orders based on customer gender?

# Methodology
## 1. Data Collection & Cleaning
Data Source: Internal sales data of the bakery from 2019 to 2022.
Cleaning Process:
Removed duplicates and empty rows.
Standardized column names and formats.
Converted date fields to appropriate datetime formats.
Checked for null values and handled them accordingly.
Ensured gender and product type fields were consistent and correctly labeled.

## 2. Data Transformation
Extracted additional fields such as:
Year, Quarter, Month, Day, and Weekday from transaction dates.
Calculated derived metrics:
Total Items Sold
Revenue (e.g., Quantity × Unit Price)
Order Count by Gender and Weekday

## 3. Pivot Tables and Chart Creation
Pivot tables were created to summarize data for each analytical question:
Sales by Year, Quarter, and Month
Weekday-wise Orders Comparison
Quarter-wise Revenue Analysis
Gender-wise Order Distribution
Each pivot table was visualized using relevant chart types:
Column charts
Line charts
Pie charts
Stacked bar charts

## 4. Dashboard Development
An interactive dashboard was created using:
Pivot charts and slicers
Filters for:
Year
Quarter
Gender
Weekday
The dashboard allows end-users to dynamically explore trends and patterns in the pie bakery's data.

# Data Used
Time Frame: 2019–2022
Fields Included:
Date of Order
Product Name
Quantity Sold
Unit Price
Customer Gender
Order ID / Transaction ID

# Deliverables
Pivot Tables
Sales breakdowns by time (year/quarter/month)
Revenue summaries
Gender-based analysis
Day-of-week order analysis

# Dashboard
Fully interactive Excel dashboard
Slicers for filtering time periods and gender
Clear visuals for insights on revenue, sales volume, and customer behavior

# Conclusion
This analysis provides a clear picture of how the bakery’s performance evolved from 2019 to 2022. With the help of pivot tables and a dynamic dashboard, the business can:
Identify seasonal peaks and low periods
Adjust production for high-performing months
Understand customer preferences by gender and day
Focus marketing efforts during high-traffic days

