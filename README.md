Project Title:
Healthcare Billing & A/R Analysis Dashboard (SQL + Power BI)Project Overview

Project Overview:
This project analyzes healthcare billing data to evaluate accounts receivable (A/R) performance, identify high-risk balances, and uncover drivers of delayed collections using SQL and Power BI.

Problem Statement:
The organization is experiencing high outstanding A/R balances, with a large portion aged over 120 days. This indicates delays in collections, operational inefficiencies, and increased financial risk.

Objective:
To analyze A/R performance and identify the key drivers of delayed collections by examining aging trends, payer behavior, and high-risk accounts.

SQL Data Preparation & Analysis:
1. Data Cleaning & Standardization - Description: Cleaned and standardized billing data to ensure consistent formats and accurate analysis.
2. A/R Aging Logic - Description: Created Days Outstanding and Aging Buckets using SQL to categorize receivables by risk levies. EX: 0-30 days -> Low risk, 120+ days -> High risk.
3. Aggregation & KPI Calculation - Description: Idenitfied high - risk receivables by filtering accounts with significant delays in payment.

Power BI Dashboard:
Key Features:
1. Executive Summary Dashboard
   Total A/R, Collection Rate, Denial Rate, Avg Days Outstanding.
2. A/R Deep Dive
   Aging distribution, High-risk claims.
3. Payer Performance
   Denial rate by payer, A/R by payer.
4. Provider Performance (Simulated)
   Revenue by provider, Efficiency analysis.

Key Insights:
A/R is heavily concentrated in the 120+ day bucket, indicating delayed collections.
Denial rates (~20%) suggest inefficiencies in claims processing.
Certain payers contribute disproportionately to outstanding balances.
High-risk accounts (90+ days) represent the greatest financial exposure.

Tools & Skills Used:
SQL (MySQL / DBeaver)
Data cleaning
CASE statements
DATEDIFF
Aggregations (SUM, GROUP BY)
Power BI
Data modeling
DAX measures (CALCULATE, TOPN, SUMMARIZE)
Dashboard design & storytelling

Business Impact:
This analysis enables stakeholders to:
Prioritize collections for high-risk accounts
Improve billing and claims processes
Reduce aging A/R balances
Enhance cash flow and operational efficiency
