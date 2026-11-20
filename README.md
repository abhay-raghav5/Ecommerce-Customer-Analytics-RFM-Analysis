# E-commerce Customer Analytics | BRD-Driven RFM Analysis

An end-to-end **BRD-driven Data Analytics Project** developed using Python, PostgreSQL, SQL, and Power BI to analyze customer purchasing behavior, identify customer segments, monitor business performance, and understand customer churn.

---

## 📌 Project Overview

This project focuses on analyzing e-commerce transactional data based on defined Business Requirements Document (BRD) objectives.

The goal is to transform raw transactional data into meaningful business insights by performing data cleaning, SQL-based analysis, RFM customer segmentation, churn identification, and interactive dashboard development.

The project follows a business-oriented analytics approach, connecting technical analysis with business requirements and decision-making.

## 🎯 Business Objectives

- Analyze customer purchasing behavior and transaction patterns.
- Identify high-value and loyal customers.
- Segment customers using RFM analysis.
- Identify customers at risk of churn.
- Analyze revenue and customer performance.
- Track key business metrics through interactive dashboards.
- Support data-driven business decision-making.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Python | Data cleaning and preprocessing |
| Pandas | Data manipulation and RFM calculations |
| Jupyter Notebook | Data analysis and implementation |
| PostgreSQL | Database management |
| SQL | Business analysis and data extraction |
| Power BI | Interactive dashboard development |
| DAX | Business metrics and KPI calculations |

## 📂 Project Workflow

### 1. Business Requirements Analysis (BRD)

Used the Business Requirements Document to understand the business objectives, analytical requirements, and expected dashboard outputs.

### 2. Data Cleaning & Preprocessing (Python)

- Loaded and inspected the e-commerce transaction dataset.
- Handled missing customer information.
- Filtered transactions with non-positive quantities.
- Converted InvoiceDate into datetime format.
- Created additional features such as InvoiceMonth and Revenue.
- Prepared the dataset for customer-level analysis.

### 3. SQL Analysis (PostgreSQL)

- Imported and analyzed transactional data using PostgreSQL.
- Performed customer and revenue-related analysis.
- Used SQL queries to extract business insights.
- Prepared data to support dashboard reporting.

### 4. RFM Analysis

Implemented RFM analysis to evaluate customer purchasing behavior using three metrics:

| Metric | Description |
|---|---|
| Recency | Number of days since the customer's last purchase |
| Frequency | Total number of unique invoices per customer |
| Monetary | Total spending of each customer |

Customers were assigned scores from 1 to 5 using quintile-based scoring.

### 5. Customer Segmentation

Customers were classified into six segments based on their RFM scores:

| Segment | Description |
|---|---|
| Champions | Recent, frequent, and high-spending customers |
| Loyal | Customers with frequent purchasing behavior |
| At Risk | Previously frequent customers with less recent purchases |
| New | Recently active customers with lower purchase frequency |
| Needs Attention | Customers who may require additional engagement |
| Lost | Customers with low recency and frequency scores |

### 6. Customer Churn Analysis

Created a churn indicator using a project-specific threshold:

`IsChurned = Recency > 90`

Customers whose last purchase was more than 90 days ago were classified as churned for this analysis.

### 7. Power BI Dashboard Development

Developed an interactive Power BI report with three pages:

## 📊 Dashboard Overview

### 1. Main Dashboard
Provides an introduction to the project and its key business metrics.

![Main Dashboard](PowerBI/Screenshots/Main_Dashboard.png)

### 2. Business Overview
Analyzes overall business and customer performance.

**Key Visualizations:**
- Total Customers
- Total Revenue
- Churned Percentage
- Average Customer Value
- Customer Distribution by Segment
- Customer Distribution by Churn Status
- Monthly, Quarterly, and Yearly Trends

![Business Overview](PowerBI/Screenshots/Business_Overview.png)

### 3. RFM Analysis
Provides detailed insights into customer segmentation and purchasing behavior.

**Key Visualizations:**
- Customer Segmentation Table
- Total Customers by Segment
- Total Revenue by Segment
- Average RFM Scores
- Average Customer Value by Segment
- Monthly, Quarterly, and Yearly Churn Trends

![RFM Analysis](PowerBI/Screenshots/RFM_Analysis.png)

## 📈 Key Business Metrics

- Total Customers
- Total Revenue
- Churn Rate
- Average Customer Value
- Recency Score
- Frequency Score
- Monetary Score
- Customer Segment Distribution

## 💡 Key Learnings

- Understanding and translating business requirements into analytical tasks.
- Data cleaning and preprocessing using Python.
- Writing SQL queries for business analysis.
- Implementing RFM-based customer segmentation.
- Identifying potentially churned customers.
- Developing business KPIs and interactive Power BI dashboards.
- Converting transactional data into actionable business insights.

## 👨‍💻 Author

**Abhay Raghav**

- GitHub: [abhay-raghav5](https://github.com/abhay-raghav5)
- LinkedIn: [Abhay Raghav](https://www.linkedin.com/in/abhay-raghav-ai/)

---

⭐ If you find this project interesting, feel free to explore the repository!
