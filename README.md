# AdventureWorks Sales Dashboard — Power BI

> *An end-to-end Business Intelligence solution connecting SQL Server with Power BI — transforming raw transactional data into strategic sales, customer, and product insights.*

---

## Overview

This project showcases a **complete Business Intelligence solution** built using the **AdventureWorks dataset**, where **SQL Server** is integrated with **Power BI** to transform raw data into meaningful, decision-ready insights.

The project covers the full BI workflow — from data extraction and transformation to modeling and interactive dashboard design — with a strong focus on **data storytelling** across sales, customer, and product performance.

---

## Objectives

-  Connect **SQL Server** with **Power BI** as a live data source
-  Perform data transformation and cleaning using **Power Query**
-  Build a **Snowflake Schema** data model for normalized, scalable analytics
-  Apply advanced **data modeling** concepts and relationship management
-  Create **interactive, multi-page dashboards**
-  Deliver compelling **data-driven storytelling** and business insights

---

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **SQL Server** | Data source and raw data storage |
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | ETL — data extraction, transformation, and loading |
| **Snowflake Schema** | Normalized data model for analytics |
| **DAX** | Calculated measures, KPIs, and dynamic logic |

---

## Data Modeling

- Designed a **Snowflake Schema** for better normalization and reduced data redundancy
- Established **relationships between fact and dimension tables**
- Optimized the model for **query performance and scalability**

### Data Model

![Data Model](https://github.com/user-attachments/assets/d5aa4806-7ab5-4b24-a384-7ed6a8662c35)

*Snowflake schema with clearly defined fact-dimension relationships across sales, customers, products, and date dimensions.*

---

## Dashboards Created

### Sales Overview Dashboard
High-level view of overall financial and sales performance across regions and time periods.

![Sales Overview](https://github.com/user-attachments/assets/510a29e8-129e-4e95-9c2d-b4e9162dfcc1)

---

### Customer Details Dashboard
Deep-dive into customer demographics, purchasing behavior, and revenue segmentation.

![Customer Details](https://github.com/user-attachments/assets/1e8b0353-27ad-491a-9ac0-2e9facb6596f)

---

### Product Details Dashboard
Explores product performance, revenue contribution, and profitability by category.

![Product Details](https://github.com/user-attachments/assets/22033eb3-d657-4fe2-bfdc-c5293388e895)

---

##  Key Insights

### 1. Financial Performance

| Metric | Value |
|---|---|
| **Total Sales** | $29.36M |
| **Total Profit** | $12.08M |
| **Profit Margin** | 41.15% |
| **Avg Order Value** | $26,120 |

>  Indicates a **high-profit, high-value transaction** business model with strong operational efficiency.

---

### 2. Regional Performance

| Region | Revenue | Notes |
|---|---|---|
| 🇺🇸 USA | $9.4M | Largest customer base |
| 🇦🇺 Australia | $9.1M | High revenue with fewer customers → highest ARPU |
| 🇬🇧 UK / 🇩🇪 Germany / 🇫🇷 France | Mid-tier | Stable, consistent markets |
| 🇨🇦 Canada | Lowest | Underperforming region |

>  Australia stands out — generating near-equal revenue to the USA with a significantly smaller customer base.

---

### 3. Sales Trends (2011–2014)

- Strong growth trajectory post-2012, **peaking in November 2013 at $1.78M**
- Clear **seasonal sales patterns** visible across all years
- January 2014 drop attributed to **incomplete data**, not business decline

>  Business demonstrates high growth potential with predictable seasonal cycles.

---

### 4. Year-over-Year Growth

| Period | Growth |
|---|---|
| 2011 → 2012 |  –17.43% decline |
| 2012 → 2013 |  +179.87% growth |
| Profit Margins | ~40% stable throughout |

>  Strong recovery from 2012 dip, with profit margins holding steady — indicating consistent operational control.

---

### 5. Customer Insights

**Demographics**
- USA holds the **largest customer base** at 7,800+ customers
- Australia achieves near-equivalent revenue with fewer customers — highest **Average Revenue Per User (ARPU)**

**Socio-Economic Segments**
-  **Bachelor's degree holders** generate the highest total revenue
-  **Professionals** are the top occupation segment — **$9.9M**
-  **Skilled Manual workers** rank second — **$6.4M**

**Gender Split**
- Nearly equal contribution: **Female $15M | Male $15M**

**Top Customer**
-  **Dalton Perez** — Most frequent buyer with **28 orders**

---

### 6. Product Insights

**Category Revenue Breakdown**

| Category | Revenue Share | Notes |
|---|---|---|
|  **Bikes** | 96.46% ($28M) | Dominant revenue driver |
| **Accessories** | Low revenue | Highest margin (~62.8%) |
| **Clothing** | Low revenue | High volume, low value |

>  **Bikes** drive revenue; **Accessories** drive margin. A classic anchor + add-on dynamic.

**2013 Growth** was driven primarily by Bike sales. The 2014 dip reflects data limitations — not a business performance issue.

---

## Key Learnings

-  Connecting **SQL Server with Power BI** for live data integration
-  Data transformation and cleansing using **Power Query (ETL)**
-  Building and optimizing a **Snowflake Schema** data model
-  Designing **multi-page interactive dashboards** in Power BI
-  Applying **data storytelling** to generate business-focused insights

---

##  Use Cases

This project is ideal for:

-  **Data Analysts & BI Developers** looking to practice end-to-end Power BI workflows
-  **Learning Power BI** from SQL connection through to dashboard delivery
-  **Practicing data modeling** with a real-world normalized schema
-  Building a **portfolio project** demonstrating full BI lifecycle skills

---

## Outcome

-  Transformed raw AdventureWorks data into **actionable, decision-ready insights**
-  Built a **scalable, normalized Snowflake Schema** data model
-  Delivered **three business-focused dashboards** covering sales, customers, and products

---

## Project Structure

```
 adventureworks-sales-dashboard
 ┣  AdventureWorks_Dashboard.pbix     # Main Power BI report file
 ┣  screenshots/                       # Dashboard preview images
 ┃   ┣  sales_overview.png
 ┃   ┣  customer_details.png
 ┃   ┣  product_details.png
 ┃   └  data_model.png
 ┗  README.md                          # Project documentation
```

---

## Connect

If you found this project useful or have suggestions, feel free to open an **Issue** or submit a **Pull Request**.
