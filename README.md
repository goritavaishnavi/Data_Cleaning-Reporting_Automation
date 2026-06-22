# Data_Cleaning-Reporting_Automation
Data Cleaning & Reporting Automation using Power BI
**Project Overview**
This project demonstrates an automated data cleaning and reporting workflow using Microsoft Power BI and Power Query. The solution transforms raw Excel data into meaningful business insights through automated data preprocessing, KPI tracking, and interactive dashboards.
The project focuses on improving data quality by handling missing values, removing duplicates, standardizing inconsistent data, and generating dynamic reports that update automatically upon data refresh.

**Objectives**
Automate data cleaning processes.
Handle missing values and duplicate records.
Standardize inconsistent data formats.
Create calculated business metrics.
Build interactive dashboards for business reporting.
Improve reporting efficiency through automation.

** Tools & Technologies**
Microsoft Power BI
Power Query
Microsoft Excel

**Dataset Information**
The dataset contains sales transaction records with the following fields:
OrderID
CustomerName
Gender
Age
City
State
Product
Category
Quantity
UnitPrice
Sales
Discount
Profit
PaymentMode
OrderStatus
OrderDate
DeliveryDate

**Data Cleaning Process (Power Query)**
The following transformations were performed:
Missing Value Handling
Replaced missing customer names with “Unknown”.
Filled missing sales values appropriately.
Duplicate Removal
Removed duplicate transaction records.
**Data Standardization**
Standardized city names.
Corrected inconsistent text values.
Applied proper data types to all columns.
**Calculated Columns**
DeliveryDays
Calculated delivery duration:
DeliveryDays = DeliveryDate - OrderDate

ProfitMargin
Calculated profit percentage:
ProfitMargin = (Profit / Sales) × 100

**Automation Workflow**
Raw Excel File
↓
Power Query Transformation
↓
Missing Values Fixed
Duplicates Removed
Data Standardized
Calculated Columns Created
↓
Dashboard Refresh
↓
Updated KPIs & Visual Reports
All cleaning steps are automatically executed whenever the dataset is refreshed.

**Dashboard Features**
KPI Cards
Total Sales
Total Profit
Total Orders
Total Customers
**Visualizations**
Sales by City
Analyzes revenue contribution from different cities.
Sales by Product
Monthly Sales Trend
Tracks sales performance over time.
Profit by Category
**Interactive Filters**
City
Product
Order Status
Order Date

**Business Insights**
The dashboard helps stakeholders:
Monitor overall sales performance.
Track profitability.
Identify top-performing products.
Analyze regional sales trends.
Monitor customer activity.
Improve decision-making through automated reporting.

 **Key Outcomes**
Reduced manual data cleaning effort.
Improved data quality and consistency.
Automated reporting workflow.
Enhanced business visibility through interactive dashboards.
Demonstrated practical Power BI and Power Query skills.

 **Skills Demonstrated**
Data Cleaning
Data Transformation
Power Query
Data Modeling
DAX Measures
Dashboard Development
Business Intelligence
Reporting Automation

**Author**
Vaishnavi Reddy
Aspiring Data Analyst | Power BI | SQL | Excel | Python
