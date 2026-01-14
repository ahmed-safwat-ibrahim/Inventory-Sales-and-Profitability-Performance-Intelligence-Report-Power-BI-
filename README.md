# Inventory, Sales & Profitability Performance Intelligence Report (Power BI)

## Project Overview

This project is an **end-to-end Business Intelligence solution built using Power BI** for an e-commerce company specializing in **Novelty Items** (packaging tools, office supplies, costumes, toys, and sweets).

The dashboard analyzes **$20M in revenue and $9.9M in net profit** to help the business:
* Understand true sales and profitability performance
* Optimize inventory and product mix
* Identify high-performing and underperforming products and regions
* Support strategic decisions with data-driven insights

The main objective was to **transform complex, scattered sales data (products, customers, regions, time)** into a **clear, decision-ready performance and profitability story**.
---
##  Business Problem
Although data existed, the business lacked:
* A clear view of **actual performance**
* A way to know **which products and regions truly drive profit**
* A direct link between **sales and profitability**
* Visibility into **what really impacts profit**

 The goal was to build a **single dashboard that tells the full story from sales to net profit**.
---
##  Key Business Metrics
* Total Sales: **$20,000,000**
* Total Quantity Sold: **~1,000,000 units**
* Net Profit: **$9,920,000**
* Profit Margin: **49.9%**

---
##  Analysis Sections
---
###  Sales Overview

**What was done:**
* Calculated total sales, quantities, and product categories
* Analyzed yearly sales trends
* Ranked products by sales
* Analyzed sales by state

**Key Findings:**
* 2015 was the **peak performance year**, followed by a decline in 2016
* Provided a clear view of **growth vs decline trends**
* Identified **Top Products** instead of relying on assumptions
* Enabled **geographic performance comparison** across states

---
###  Profit Analysis
**What was done:**
* Separated sales from costs and calculated:
  * Total Cost
  * Total Profit
  * Profitability %
* Compared profit vs sales by:
  * Year
  * Product
  * State
  * 
**Key Findings:**
* Net profit reached **$9.92M with ~50% margin**
* **California** is the top-performing state by profit
* Revealed that:

  > Not every high-selling product is necessarily profitable
---

### Detailed Report (Table View)
**Features:**
* Detailed table including:
  * Sales
  * Quantity
  * Cost
  * Profitability
* Multi-year comparison
* Drill-down capability from:

  * Region → State → City
**Added:**
* **Decomposition Tree** to analyze contribution from region level down to each city and understand exactly **who contributed what** to the $20M revenue.

---
### Key Influencers (AI Insights)

**Purpose:**
* Identify **what really increases profit**
**Key Insight:**

* When sold quantity is between **26 and 120 units**, profitability becomes **significantly higher than average**

This insight was used to define **optimal and profitable stock thresholds**.

---

### Treemap & Distribution

**Goal:**
* Understand whether customers prefer:
  * Buying **per unit (Each)**
  * Or **per carton**
    
**Finding:**
* **Each-unit sales dominate** in most states, impacting packaging and pricing strategy.
---
## Data Model & Architecture
* Built using **Star Schema**
* Central Fact Table connected to:
  * Products
  * Customers
  * Geography
  * Date
* One-to-Many relationships
* Custom Date Dimension for:

  * Time intelligence
  * Trend analysis
  * Year-over-year comparisons

##  Tools & Technologies

* Power BI Desktop
* DAX (Measures, KPIs, Profitability Calculations)
* Power Query (ETL & Data Cleaning)
* Star Schema Data Modeling
* Decomposition Tree & Key Influencers visuals

---

##  Business Impact
* Identified **Air Cushion Machine** as the top revenue-generating product
* Detected **underperforming states** (Nevada, Hawaii) for targeted marketing
* Confirmed **strong and stable ~50% profit margin**
* Defined **optimal sales quantity range (26–120 units)** to maximize profitability
* Improved:
  * Inventory planning
  * Product strategy
  * Marketing focus
  * Profit-driven decision making
---
##  Deliverables
* Interactive Power BI Dashboard
* Cleaned and modeled dataset
* Executive-level KPI views
* Drill-down & AI-powered insights
* Turn this into **interview storytelling format**
* Prepare **portfolio presentation slides**
