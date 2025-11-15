# Customer-behavior-analysis
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.

# Project Overview
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:
  - Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.
  - Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.
  - Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.
  -  Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually               communicates insights and actionable recommendations to stakeholders.
# Dataset
Source: Provided CSV file (customer_shopping_behavior.csv).
Key Columns: customer_id, gender, age, category, item_purchased, quantity, price, discount, purchase_date, payment_method, etc
**Problem Statement:**
Understand what drives purchases, which categories/items dominate, which customer groups spend the most, and how discounts influence buying behavior.

# Tools & Technologies
  - Python (Pandas, NumPy) – Data loading, EDA, cleaning.
  - SQL Server – Structured querying, aggregations, segmentation.
  - Power BI – Interactive dashboard creation.
  - Gamma.app – Automated presentation generation.
  - Jupyter Notebook – Development environment.

# Project Steps
1. Load Data in Python
   - Imported dataset using pandas.read_csv()
   - Inspected structure, checked datatypes, and validated column consistency

2. Exploratory Data Analysis (EDA)
   - Summary statistics for numerical and categorical features
   - Null value analysis and distribution checks
   - Visualizations: Category-wise purchase counts, Revenue by item, Discount vs. quantity correlation, Customer age group distribution

3. Data Cleaning
   - Missing value handling (mean/median imputation or removal)
   - Standardizing category labels
   - Creating new derived metrics

4. SQL Analysis (SQL Server)
Loaded the cleaned dataset into SQL Server to run analytical queries such as:
   - Top 3 items purchased per category
   - Revenue by payment method
   - Customer segmentation by spend
   - Most profitable categories
   - Discount impact analysis

5. Dashboard in Power BI
   - Created an interactive dashboard showing:
   - KPIs: Total Revenue, Avg Order Value, Repeat Customers
   - Category-wise and item-wise performance
   - Revenue by gender, age group, and payment method

6. Business Report
   - A structured insight report summarizing:
   - Overall customer behavior patterns
   - Drivers of sales and revenue
   - Actionable recommendations
   - High-level takeaways for business stakeholders

7. Presentation (Gamma)
   - Built a recruiter-friendly or stakeholder-ready presentation including:
   - Problem statement
   - Workflow
   - Key insights
   - Recommendations
   - Next steps

# Dashboards
The Power BI dashboard includes:
  - Category Performance Overview
  - Top Selling Products
  - Customer Demographics Insights
  - Discount Impact Visualization
