#  Sales Performance Analysis Dashboard (Excel)

This project presents a comprehensive sales performance analysis dashboard built using Excel/WPS Spreadsheet. The analysis focuses on transactional sales data from a multi-regional electronics distributor and demonstrates data cleaning, business analysis, scenario modeling, and dashboard development skills.

---

#  Project Overview

The dataset contained transactional sales records with intentional data quality issues such as duplicates, missing values, incorrect formats, and pricing inconsistencies.

The objectives of the project were to:

- Clean and prepare the dataset
- Perform exploratory and business analysis
- Build a What-If scenario model
- Develop an interactive dashboard
- Generate business insights and recommendations

---

#  Data Cleaning & Preparation

Several data quality issues were identified and resolved:

## Data Issues Found
- Duplicate records
- Missing values in City, Salesperson, and Channel columns
- Dates stored as text
- Negative Unit Price values
- Excessive Discount Percentage values
- Invalid date relationships

## Cleaning Steps Performed
- Removed duplicate rows
- Standardized numeric and date formats
- Converted negative Unit Prices to positive values
- Corrected invalid dates
- Standardized discount percentages
- Handled missing categorical values using logical assumptions

---

#  Feature Engineering

Additional analytical columns were created to improve analysis:

- LeadTimeDays
- Month (MMM-YYYY)
- Quarter
- Price Band
- Gross Profit
- Revenue per Order
- On-Time Flag

---

#  Analysis Performed

## 1. Cohort Analysis
- Identified the first sales month per country
- Tracked revenue performance over time

## 2. ABC Analysis
Products were classified into:
- A Class → Top 80% Revenue Contributors
- B Class → Next 15%
- C Class → Remaining 5%

## 3. Salesperson Productivity Analysis
Calculated:
- Revenue per Order
- Orders per Month
- Gross Profit per Order

## 4. Channel Mix Analysis
Compared:
- Online vs Retail revenue contribution
- Regional channel performance

## 5. Service Level Analysis
Measured:
- Percentage of orders delivered within 7 days

## 6. Price Compliance Analysis
Identified:
- Transactions with excessive discounts
- Regional and salesperson discount outliers



#  Scenario Modeling

A What-If model was developed to simulate changing business conditions.

## Scenario Inputs
- Discount Cap (0%–25%)
- Cost Inflation (0%–15%)
- Quantity Uplift (0%–20%)

## Scenario Outputs
- Adjusted Revenue
- Adjusted Profit
- Profitability Sensitivity

### Key Finding
High discounts combined with increased costs can significantly reduce profitability and may result in negative profit margins.

---
# Dashboard Preview 
![Dashboard](https://github.com/stacymoraa56-eng/sales-performance-analysis-excel/blob/main/Sales%20Performance%20Analysis%20Dashboard.png)


#  Dashboard Features

The dashboard includes:

## KPIs
- Total Revenue
- Gross Profit
- Margin %
- Average Order Value
- On-Time Delivery %

## Visualizations
- Revenue by Month
- Profit by Region & Channel
- Top 10 SKUs by Revenue
- Discount Outliers Scatter Plot

## Interactivity
- Region Filters
- Country Filters
- Channel Filters
- Product Category Filters
- Salesperson Filters

---

#  Key Insights

- A small number of SKUs generated the majority of revenue
- High discounting reduced profitability in several regions
- Online channels outperformed retail in revenue contribution
- Some regions experienced lower service-level performance
- Revenue concentration was highest among A-Class products

---

#  Recommendations

Based on the analysis, the following recommendations were proposed:

- Reduce excessive discounting to protect profit margins
- Focus marketing efforts on top-performing A-Class products
- Improve delivery efficiency in low-performing regions
- Monitor salesperson discount behavior for compliance
- Expand successful online sales strategies across regions
- Use scenario modeling before implementing pricing decisions

---

#  Tools Used

- Excel 
- Pivot Tables
- Pivot Charts
- Data Cleaning & Transformation
- Dashboard Design
- Scenario Modeling
- Conditional Formatting

---

#  Conclusion

This project demonstrates practical business analytics skills including:

- Data cleaning and preparation
- Exploratory analysis
- Dashboard development
- Scenario modeling
- Insight generation
- Business recommendation development

The dashboard supports data-driven decision-making and highlights the impact of pricing, channels, and operational efficiency on business performance.

