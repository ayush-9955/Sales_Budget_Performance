# 📊 Sales_Budget_Performance

## 📝 Project Overview
This project is an end-to-end data analysis of retail sales performance. By examining a robust dataset containing product details, campaign metrics, regional geography, and unit financials, this project aims to uncover actionable business insights regarding profitability, regional dominance, and product performance.

## 🗄️ Dataset Description
The dataset consists of transactional sales records with the following key data points:
* **Product Data:** `ProductID`, `Product` (e.g., Maximus Urban), `Category`, `Segment`, `Manufacturer`
* **Financials:** `Units` sold, `Unit Cost`, `Unit Price`
* **Geography:** `ZipCode`, `City`, `State`, `Region`, `District`, `Country` (e.g., US East Region focus)
* **Marketing & Customers:** `CustomerID`, `Campaign` IDs, `Date` of transaction

## 🎯 Key Objectives
1. **Profitability Analysis:** Calculate and analyze total revenue, total cost, and gross profit margins across different product segments.
2. **Geographical Insights:** Identify top-performing regions, states, and districts.
3. **Product Performance:** Determine which categories and specific products drive the most volume and highest margins.
4. **Campaign Effectiveness:** Evaluate sales spikes and unit volume against specific marketing campaigns.

## 📈 Visualization & Dashboard Structure
To provide a comprehensive view of the business, the reporting is broken down into a structured, 5-page interactive dashboard:

1. **Executive Summary (Overview):** * High-level KPIs: Total Revenue, Total Profit, Profit Margin %, Total Units Sold.
   * Trend line showing revenue over time.
2. **Product & Category Deep Dive:** * Bar charts comparing revenue and profit by `Category` and `Segment`.
   * Matrix/Pivot tables showing top 10 and bottom 10 performing products.
3. **Regional Performance Map:**
   * Geospatial map visualizing sales volume by `State` and `City`.
   * Treemap of sales distribution by `Region` and `District`.
4. **Campaign & Customer Insights:**
   * Analysis of unit sales grouped by `Campaign` ID to measure marketing ROI.
   * Customer purchase frequency distribution.
5. **Cost vs. Pricing Analysis:**
   * Scatter plot analyzing the relationship between `Unit Cost`, `Unit Price`, and overall volume.

## 🛠️ Tech Stack & Tools
* **Data Cleaning & Preparation:** Python (Pandas) / Power Query
* **Exploratory Data Analysis (EDA):** Excel (Pivot Tables)
* **Interactive Visualization:** Power BI
* **Calculations:** DAX (Data Analysis Expressions) for custom business metrics

1. Clone the repository to your local machine.
2. Ensure the raw data file (e.g., `sales_data.csv` or `.xlsx`) is located in the `/data` folder.
3. Open the `.pbix` file to view the interactive dashboard, or run the Jupyter Notebook (`.ipynb`) to see the Python data cleaning and initial pivot table steps.
