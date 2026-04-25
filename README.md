# Hotel Operations & Budget Variance Engine

## Project Overview
This exploratory project leverages a hospitality dataset to automate the tracking of revenue and expenses across multiple business units. By bridging the gap between raw database code (SQL) and executive-level insights, this project identifies growth trends, budget overruns, and operational risks.

## The Data
* fact_revenue.csv - Transactional income records including: unit identifier (Breakfast, Hall, Restaurant, etc.), amount, and date.
* fact_expenses.csv - Detailed cost records including: COGS (Food/Beverage), labor costs, and maintenance expenses.
***fact_budget.csv** - Financial targets including: planned revenue and expense benchmarks for variance comparison.
***Note**: All data represents multi-source financial metrics. Analysis focuses on translating raw ledger entries into "Source of Truth" dashboards for operational stakeholders. This dataset is synthenthically generated. 

## Business Questions Explored
* Unit Performance: In which business units are we seeing the highest projected growth? Which units require resource re-allocation?
* Budget Accountability: How are units performing against their planned budget? Which regions have cost overruns that require immediate review?
* Year-over-Year (YoY) Trends: How do current quarterly expenses (COGS/Labor) compare to the previous year's performance?

## Key Insights

### Revenue Performance & Projections
* Top Growth Units: Room Service leads with a **22% projected growth rate**, followed by Breakfast at **20%**. 
* Stable Performers**: The Restaurant and Rooftop bar units show consistent **14%** growth trajectories.

### Budget vs. Actual Variance
* Favorable Trends: The Breakfast unit shows a **3% favorable revenue variance**, performing above the established budget.
* Operational Risks: The Rooftop unit is currently experiencing an **18% unfavorable variance (cost overrun)**, suggesting a need for tighter expense controls.

###COGS & Expense Analysis
* High Variance: Banquet Direct COGS (Food and Beverage) has increased **74% YoY** (Q1 2025 vs Q1 2026).
* fficiency Gains: Outstanding Maintenance expenses were reduced by **100%** in the current period, indicating improved facility management.

## Demonstrated Skills
* Business Acumen: Providing actionable analysis for stakeholder reviews and site controller meetings.
* KPIs & Operational Metrics**: Variance analysis, Growth Rates, Cost Overrun Tracking, and YoY Trends.
* SQL Proficiency: Complex queries, multi-table joins, CASE statement pivoting, and aggregations.

##SQL Functions & Analytical Concepts
* Data Normalization
* Aggregate Functions (SUM, ROUND, AVG)
* Left Joins (Unifying Budget vs. Actuals)
* CASE WHEN Statements (Pivoting rows to columns for time-series analysis)
* Common Table Expressions (CTEs)
* Subqueries
* Variance & Growth Calculations
