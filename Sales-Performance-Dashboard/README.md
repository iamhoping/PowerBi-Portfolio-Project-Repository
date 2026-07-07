#  Sales Performance Dashboard | Power BI

##  Project Overview

The **Sales Performance Dashboard** is an interactive Business Intelligence (BI) solution developed using **Power BI** to analyze sales performance from the **Sample Superstore** dataset. The dashboard provides business users with a comprehensive view of key sales metrics, customer behavior, product performance, and regional sales distribution through interactive visualizations.

This project demonstrates the complete Power BI workflow—from data transformation and modeling to DAX calculations and dashboard design—turning raw transactional data into meaningful business insights.

---

##  Business Objective

The objective of this project is to help stakeholders monitor business performance by answering critical sales-related questions through an interactive dashboard.

The dashboard enables users to:

- Monitor overall sales and profit performance.
- Identify top-performing product categories and products.
- Analyze monthly sales trends.
- Compare sales across customer segments.
- Evaluate regional sales performance.
- Support data-driven business decisions through interactive reporting.

## Dashboard Preview
<p align="center"> <img src="Screenshot 2026-07-07 145310.png" width="850" alt=""> </p>


##  Dataset Information

| Item | Description |
|------|-------------|
| **Dataset** | Sample Superstore |
| **Records** | ~9,994 Sales Transactions |
| **File Type** | Excel (.csv) |
| **Tool Used** | Microsoft Power BI Desktop |

### Dataset Features

- Order Information
- Customer Information
- Product Information
- Sales Metrics
- Profit Metrics
- Shipping Information
- Geographic Information

---

#  Data Preparation

The dataset was transformed and prepared using **Power Query** before creating the dashboard.

### Data Cleaning Process

- Verified all column data types
- Validated dataset quality (100% valid records)
- Removed blank rows
- Renamed the query to **Orders**
- Created additional analytical columns:
  - Profit Margin
  - Order Year
  - Order Month
  - Order Month Number
  - Order Quarter
  - Order Day


#  Data Modeling

A **Star Schema** was implemented to improve model performance and support advanced DAX calculations.

### Data Model

```
Date
   │
   ▼
Orders
```

The **Date Table** was created using DAX and linked to the **Orders** table through the **Order Date** field.

---

#  DAX Measures

The following measures were created to calculate key business metrics.

| Measure | Description |
|----------|-------------|
| Total Sales | Total revenue generated |
| Total Profit | Total profit earned |
| Total Orders | Number of unique orders |
| Total Customers | Number of unique customers |
| Total Quantity | Total products sold |
| Average Order Value | Average revenue per order |
| Profit Margin % | Profit as a percentage of sales |
| Average Sales per Customer | Average revenue per customer |
| Total Discount | Total discount given |
| Average Discount | Average discount percentage |

---

#  Dashboard Features

### KPI Cards

-  Total Sales
-  Total Profit
-  Total Orders
-  Total Customers
-  Profit Margin

### Visualizations

- Monthly Sales Trend
- Sales by Customer Segment
- Sales by Category
- Most Profitable Sub-Categories
- Top 10 Products by Sales
- Sales by Region

### Interactive Filters

- Year
- Category
- Segment
- Region

---

#  Key Business Insights

- Technology generated the highest sales among all product categories.
- Consumer customers contributed the largest share of total revenue.
- Sales increased significantly during the final months of the year, indicating seasonal demand.
- Copiers generated the highest profit among all product sub-categories.
- A small number of products accounted for a large percentage of total sales.
- Regional performance varied, providing opportunities for targeted marketing strategies.
- Interactive slicers allow users to explore sales performance across different years, customer segments, product categories, and regions.

---

#  Skills Demonstrated

### Power BI

- Interactive Dashboard Development
- Data Visualization
- KPI Reporting
- Dashboard Design
- Report Optimization

### Power Query

- Data Cleaning
- Data Transformation
- Custom Columns
- Data Validation

### Data Modeling

- Star Schema
- Relationships
- Date Dimension
- Best Practices

### DAX

- Aggregate Functions
- DISTINCTCOUNT
- DIVIDE
- Business KPIs
- Time Intelligence Preparation

---

#  Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
