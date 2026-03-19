# Global Super Store Retail Analytics Dashboard

A two-page interactive Power BI dashboard built on the Global Superstore dataset (2011–2014), designed as a junior data analytics portfolio project.

---

## Dashboard Pages

### Page 1 — Sales Overview
Provides a high-level view of overall business performance across products, categories, regions, and markets.

**KPIs:** Total Sales, Total Profit, Total Orders, Profit Margin

**Charts:**
- Total Sales by Month and Year (YoY multi-line chart — 2011 to 2014)
- Total Sales by Category (donut chart)
- Total Sales by Region (bar chart)
- Total Sales by Market (line chart)
- Top 7 Products by Sales (horizontal bar chart)

**Key Insights:**
- Sales peak during year-end months, indicating strong seasonal demand
- Technology products drive the highest sales and profit performance
- The Central region contributes stronger overall performance compared to other regions

---

### Page 2 — Customer Insights
Focuses on customer behaviour, segmentation, and order patterns.

**KPIs:** Total Sales, Total Customers, Total Orders, Sales per Customer

**Charts:**
- Total Sales by Region and Segment (clustered bar chart)
- Total Sales by Segment (donut chart)
- Total Orders by Month (line chart)
- Repeat vs New Customer Orders (donut chart)
- Top 7 Customers by Sales (horizontal bar chart)

**Key Insights:**
- Consumer segment leads with 51% of total sales across all regions
- Top 7 customers are disproportionately high-value — Tom Ashbrook alone exceeds $40K
- Orders peak in December and drop sharply through February, a clear post-holiday dip
- 95.74% of orders come from repeat customers (ordering more than 10 times), confirming an exceptionally loyal customer base

---

## Files in This Repository

| File | Description |
|------|-------------|
| `GlobalSuperstore.csv` | Raw dataset used to build the dashboard |
| `GlobalStores_dashboard.pbix` | Power BI dashboard file (open with Power BI Desktop) |
| `GlobalStores_dashboard.pdf` | Exported PDF preview of both dashboard pages |
| `README.md` | Project documentation |

---

## Dataset

**Source:** Global Superstore dataset — a widely used public dataset for data analytics practice.

**Period covered:** January 2011 – December 2014

**Key fields:** Order ID, Order Date, Customer ID, Customer Name, Segment, Region, Market, Product Name, Category, Sub-Category, Sales, Profit, Discount, Quantity

---

## Tools Used

- **Power BI Desktop** — dashboard development and visualisation
- **DAX** — calculated columns (e.g. Customer Type classification)
- **Microsoft Excel / CSV** — data source

---

## How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `GlobalStores_dashboard.pbix` in Power BI Desktop
4. If prompted to refresh data, point it to the `GlobalSuperstore.csv` file in the same folder

---

## Shalmalee Thakur

Built as part of a junior data analytics portfolio project.  
Tool: Power BI Desktop 
Dataset: Global Superstore (2011–2014)
