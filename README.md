#  Chinko-Data-Analysis-Project

##  Project Overview

**Chinko-Data-Analysis-Project** is an end-to-end Business Intelligence project that analyzes sales, customer behavior, employee performance, and product trends using the **Chinko** digital music store database.

The project combines **SQL**, **Python**, and **Power BI** to extract, transform, and visualize business data. SQL was used to query and aggregate the data, Python was used to connect the Chinko SQLite database to Power BI, and Power BI was used to create interactive dashboards that provide actionable business insights.

---

##  Project Objectives

The objectives of this project are to:

- Analyze sales and revenue performance over time.
- Identify high-value customers through Lifetime Value (LTV).
- Evaluate sales support representative performance.
- Discover customer purchasing patterns.
- Identify top-performing artists, tracks, and genres.
- Understand customer preferences for digital media formats.
- Build an interactive Power BI dashboard for business decision-making.

---

##  Dataset Description

The **Chinko** dataset simulates a digital music store similar to iTunes and contains transactional data across multiple business entities.

### Database Tables

| Table | Description |
|--------|-------------|
| Customers | Customer demographic and location information |
| Employees | Sales support representatives |
| Invoices | Customer purchase transactions |
| Invoice_Items | Individual products sold |
| Tracks | Music tracks |
| Albums | Album information |
| Artists | Artist information |
| Genres | Music genres |
| Media_Types | Digital audio formats |
| Playlists | Music playlists |

---

#  Tech Stack

| Technology | Purpose |
|------------|---------|
| **SQL** | Data extraction, transformation, aggregation, and analysis |
| **SQLite** | Chinko relational database |
| **Python** | Connected the SQLite database to Power BI using a Python script |
| **Power BI** | Interactive dashboard development and data visualization |
| **Git & GitHub** | Version control and project documentation |

---

#  Data Workflow

```
Chinko SQLite Database
          │
          ▼
    Python Script
(Database Connection)
          │
          ▼
      Power BI
(Data Transformation)
          │
          ▼
 Interactive Dashboards
          │
          ▼
 Business Insights
```

---

#  Dashboard Reports

## 1️ Sales & Revenue Performance Report

This dashboard provides insights into the financial performance of the digital music store.

### Key Metrics

-  Total Revenue
-  Monthly Revenue Trends
-  Yearly Revenue Trends
-  Average Order Value (AOV)
-  Revenue by Country
-  Revenue by City

### Business Questions

- How has revenue changed over time?
- Which countries generate the highest revenue?
- Which cities are the strongest markets?
- What is the average customer invoice value?

---

##  Customer Insights & Engagement Report

This dashboard focuses on customer value and employee performance.

### Key Metrics

- Customer Lifetime Value (LTV)
- Top Spending Customers
- Customers by Country
- Revenue by Sales Representative

### Business Questions

- Who are the most valuable customers?
- Which countries have the largest customer base?
- Which support representatives generate the most revenue?

---

##  Product & Inventory Optimization Report

This dashboard analyzes customer preferences and product performance.

### Key Metrics

- Top-Selling Genres
- Top-Selling Artists
- Best-Selling Tracks
- Media Type Preferences

### Business Questions

- Which music genres sell the most?
- Which artists generate the highest revenue?
- Which tracks are purchased most frequently?
- Which digital media formats are preferred by customers?

---

#  Key Performance Indicators (KPIs)

- Total Revenue
- Monthly Revenue
- Yearly Revenue
- Average Order Value (AOV)
- Customer Lifetime Value (LTV)
- Revenue by Country
- Revenue by City
- Revenue by Employee
- Top Customers
- Top Genres
- Top Artists
- Top Tracks
- Media Type Performance

---

##  Python Integration with Power BI

Instead of importing the data directly into Power BI using built-in database connectors, this project uses **Power BI's "Get Data → Python Script"** option to establish a connection to the **Chinko SQLite database**.

The Python script serves as a bridge between the SQLite database and Power BI, allowing SQL query results to be imported directly into the Power BI data model for visualization and analysis.

### Python's Role

- Connected Power BI to the Chinko SQLite database.
- Retrieved data from the database using a Python script.
- Imported the query results into Power BI for reporting and dashboard creation.

### Power BI Workflow

```text
Power BI
   │
   ▼
Get Data → Python Script
   │
   ▼
Connect to Chinko SQLite Database
   │
   ▼
Import Data into Power BI
   │
   ▼
Data Transformation & Dashboard Development
```


---

# 📈 Power BI Dashboard Features

The Power BI dashboards include:

- Interactive slicers and filters
- KPI cards
- Line charts for revenue trends
- Bar and column charts
- Customer ranking tables
- Product performance dashboards
- Dynamic drill-through capabilities

---

#  Key Business Insights

The project enables stakeholders to:

- Monitor revenue growth over time.
- Identify top-performing geographic markets.
- Recognize high-value customers.
- Measure employee sales performance.
- Understand customer purchasing preferences.
- Identify the most popular music genres and artists.
- Optimize digital inventory based on media format demand.

---

#  Future Enhancements

Future improvements could include:

- Predictive sales forecasting using Python.
- Customer segmentation with RFM analysis.
- Recommendation engine for music purchases.
- Automated dashboard refresh using Power BI Service.
- Advanced analytics using DAX and Power Query.
- Machine learning models for customer behavior prediction.

---

#  Skills Demonstrated

This project demonstrates expertise in:

- SQL Data Analysis
- Relational Database Management
- Python Data Integration
- Power BI Dashboard Development
- Business Intelligence Reporting
- KPI Design and Analysis
- Data Visualization
- Data Storytelling
- ETL Concepts
- Business Analytics

---

## Dashboard Preview

### Sales Dashboard

![Sales_Dashboard](Sales_Dashboard.png)

##  Author

**Emmanuel Egabor**

**MSc Data Science | Data Analyst | Business Intelligence Analyst**

###  Connect with Me

- **GitHub:** https://github.com/EmmanuelEgabor
- **LinkedIn:** *https://www.linkedin.com/in/egabor-emmanuel/*

---

##  Support

If you found this project useful, please consider giving it a ** Star** on GitHub. Your support is greatly appreciated!
