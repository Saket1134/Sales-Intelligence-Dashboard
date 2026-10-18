
# Sales Intelligence Dashboard | Power BI

## 📊 Project Overview

The **Sales Intelligence Dashboard** is an interactive business intelligence project developed using Microsoft Power BI to analyze sales performance, revenue trends, product performance, and regional sales.

The dashboard transforms raw sales data into meaningful visual insights, helping businesses monitor key performance indicators (KPIs), identify trends, and make data-driven decisions.

## 🎯 Project Objectives

- Analyze overall sales performance and revenue trends.
- Identify top-performing products and product categories.
- Compare sales performance across different regions.
- Track key business metrics using KPI cards.
- Enable interactive data exploration through slicers and filters.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization
- **DAX** – Calculated measures and KPI calculations
- **Power Query** – Data cleaning and transformation
- **Data Visualization** – Charts, graphs, and interactive reports
- **Excel / CSV** – Sales data source

## ✨ Key Features

- **KPI Cards:** Display important sales metrics at a glance.
- **Revenue Analysis:** Analyze revenue trends and sales performance.
- **Product Analysis:** Identify high-performing products and categories.
- **Regional Analysis:** Compare sales across different geographical regions.
- **Interactive Slicers:** Filter dashboard data based on selected criteria.
- **DAX Measures:** Calculate key metrics for business performance analysis.

## 📈 Key Performance Indicators

The dashboard can include the following KPIs, depending on the available dataset:

- Total Sales
- Total Revenue
- Total Orders
- Average Order Value
- Sales by Product
- Sales by Region
- Monthly Revenue Trends

## 🧮 DAX Measures

Example DAX measures that can be used in the dashboard:

### Total Sales
```dax
Total Sales = SUM(Sales[Sales])
```

### Total Orders
```dax
Total Orders = DISTINCTCOUNT(Sales[Order ID])
```

### Average Order Value
```dax
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
```

**Note:** Update the table and column names to match your actual dataset. These are example measures, not claims about the exact measures implemented in the report.

## 📂 Project Structure

```text
Sales-Intelligence-Dashboard/
│
├── README.md
├── Sales_Dashboard.pbix
├── sales_data.csv
└── screenshots/
    └── dashboard.png
```

*Include only the files that actually exist in your repository. Replace the example filenames with your actual filenames.*

## 🚀 How to Use

1. Clone or download this repository.
2. Download and install Power BI Desktop on a supported Windows computer.
3. Open the `.pbix` file in Power BI Desktop.
4. If required, update the dataset path and refresh the data.
5. Explore the dashboard using the charts, KPI cards, and slicers.

**Note for Mac users:** Power BI Desktop does not have a native macOS version. You can use a Windows computer or a compatible Windows virtual machine to open and edit `.pbix` files.

## 💡 Business Value

This project demonstrates how business intelligence tools can convert sales data into actionable insights. It helps stakeholders understand revenue patterns, evaluate product performance, compare regional results, and monitor business KPIs.

## 🎓 Skills Demonstrated

- Data Cleaning and Transformation
- Exploratory Data Analysis
- Power BI Dashboard Development
- DAX Measures
- KPI Reporting
- Data Visualization
- Business Insights and Analytical Thinking
