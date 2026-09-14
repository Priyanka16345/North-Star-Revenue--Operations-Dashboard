# North-Star-Revenue--Operations-Dashboard
Interactive B2B SaaS Revenue Operations dashboard built in Excel using Power Query, PivotTables, formulas, slicers, and KPI analysis to evaluate pipeline, revenue, quota, rep, product, and regional performance.
# Revenue Operations Dashboard — B2B SaaS

An Excel-based Revenue Operations project built around a fictional B2B SaaS company.

The goal of this project was not just to create an attractive dashboard. I wanted to build something that shows how Excel can be used to answer practical RevOps questions around pipeline, revenue, quota attainment, sales performance, products, and regions.

The project takes sales data from a raw dataset, cleans and prepares it, calculates business KPIs, builds PivotTable-based reports, and finally turns those outputs into an interactive executive dashboard.

# Business Problem

Sales leadership needs a simple way to understand:

- How much open pipeline do we currently have?
- How much revenue has been closed?
- Are we on track against quota?
- What does the weighted pipeline look like?
- Which sales reps are performing best?
- Which products are generating the most revenue?
- Which regions are contributing the most revenue?
- How is revenue changing over time?
- Where are potential pipeline risks?

Instead of looking through raw opportunity data, this project brings these questions together into one reporting workflow.

---

# What I Built

The workbook follows a simple reporting flow:

**Raw Data → Data Cleaning → KPI Analysis → Reporting → Executive Dashboard**

# 1. Data Preparation

Used Excel Power Query to clean and prepare the sales and rep target data.

The cleaning process included:

- Handling missing values
- Cleaning data types
- Standardizing dates
- Preparing numeric fields
- Checking inconsistent values
- Creating analysis-ready tables

# 2. Executive KPI Analysis

Built an Executive KPI section covering metrics such as:

- Open Pipeline
- Closed Won Revenue
- Closed Lost Revenue
- Win Rate
- Weighted Pipeline
- Rep Performance
- Product-level analysis

# 3. Reporting Layer

Built PivotTables to analyze:

- Revenue by Product
- Revenue by Region
- Revenue by Sales Rep
- Pipeline by Stage
- Monthly Revenue Trend


# 4. Interactive Dashboard

The final dashboard brings the analysis together using:

- PivotCharts
- Slicers
- Conditional formatting
- Dynamic reporting views

The dashboard is designed as an executive-level view rather than simply a collection of charts.

# Excel Skills Demonstrated

This project was intentionally built to demonstrate practical Excel skills relevant to a Revenue Operations Analyst role.

# Formulas & Functions

- SUM
- SUMIFS
- COUNTIFS
- AVERAGEIFS
- IF
- Nested IF
- IFERROR
- VLOOKUP
- INDEX + MATCH
- UNIQUE

# Data Preparation

- Power Query
- Data type transformation
- Missing-value handling
- Data cleaning

# Analysis & Reporting

- PivotTables
- PivotCharts
- Slicers
- Data validation
- Conditional formatting
- KPI calculations

# Key RevOps Metrics

### Open Pipeline

Open opportunities that have not yet been Closed Won or Closed Lost.

### Weighted Pipeline

Weighted pipeline estimates the expected value of the open pipeline by applying the probability of each opportunity.

**Weighted Pipeline = Opportunity Amount × Probability**

### Win Rate

Win rate is calculated using closed opportunities:

**Win Rate = Closed Won Deals / (Closed Won Deals + Closed Lost Deals)**

### Remaining Quota

**Remaining Quota = Total Quota − Closed Won Revenue**

If closed-won revenue exceeds quota, remaining quota can become negative, indicating that the team has already exceeded its target.

# Dashboard Views

### Revenue by Region

Highlights the regions generating the highest revenue.

### Rep Performance

Compares sales representatives based on closed-won revenue.

### Pipeline by Stage

Provides visibility into where opportunities are concentrated across the sales funnel.

### Monthly Revenue Trend

Shows how revenue changes over time and helps identify periods of stronger or weaker performance.

### Product × Region

Combines product and regional performance to identify areas where specific products perform particularly well.


# Business Questions This Dashboard Can Answer

The dashboard is designed to support questions such as:

1. Which region is generating the most revenue?
2. Which product contributes the most revenue?
3. Which sales reps are leading in closed-won revenue?
4. How much pipeline is currently open?
5. How much of the pipeline is realistically expected to convert?
6. Where is pipeline concentrated within the sales funnel?
7. Are there regions or products that may require additional attention?
8. How is revenue trending over time?

# Workbook Structure

The workbook is organized into seven main layers:

| Sheet | Purpose |
|---|---|
| Deals_Raw | Original opportunity/deal data |
| Rep_Targets | Sales representative quota/target data |
| Clean_Deals | Power Query-cleaned deal data |
| Cleaned_Rep_Target | Power Query-cleaned target data |
| Executive KPI | Formula-based KPI and business analysis |
| Reports | PivotTable-based reporting layer |
| Dashboard | Final interactive executive dashboard |

This separation keeps the raw data, calculations, reporting and visualization layers distinct.

---

# Why I Built This

I created this project as part of my preparation for a Revenue Operations Analyst role.

One thing I wanted to avoid was building a project that simply demonstrated Excel functions without showing why those functions matter to a business.

The focus here was therefore on connecting Excel skills with actual RevOps questions:

**What is happening? - Why is it happening? - Where is it happening? - What should the business pay attention to?**

# Business Insights

The dashboard was designed to help sales leadership move from reporting to decision-making.

## 1. Revenue Concentration

Revenue by region can highlight markets that are already producing strong results and may justify additional sales or marketing investment.

## 2. Product Performance

Revenue by product helps identify which products are contributing most to the business and where cross-sell or upsell opportunities may exist.

## 3. Rep Performance

Replevel performance can highlight top performers as well as reps who may require additional coaching or pipeline support.

## 4. Pipeline Health

Open pipeline and weighted pipeline provide two different views of future revenue potential.

Open pipeline shows the total opportunity value, while weighted pipeline provides a probability-adjusted view.

## 5. Funnel Risk

Pipeline by stage helps identify whether opportunities are concentrated in early stages or whether sufficient value is progressing toward Proposal and Negotiation.

## 6. Management Action

The dashboard should not be treated as a report that simply describes what happened.

The purpose is to help management identify:

- Where to invest
- Where pipeline is at risk
- Which reps may need support
- Which products are gaining traction
- Which regions deserve additional attention


# Tools

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel formulas
- Data validation
- Conditional formatting

The workbook was designed to be usable on Excel for Mac.

# Dataset

The dataset used in this project represents a fictional B2B SaaS sales organization.

It is intended for portfolio and learning purposes and does not contain real customer or company data.

# Project Outcome

This project helped me practice the complete reporting workflow rather than focusing on individual Excel features in isolation:

**Data - Cleaning - Analysis - Reporting - Visualization - Business Interpretation**

The final dashboard provides an executive view of sales performance while the underlying workbook retains the detailed calculations and reporting logic used to produce it.


# Author

Built as a Revenue Operations portfolio project.
