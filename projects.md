---
title: "Projects"
permalink: /projects/
layout: single
---

Hands-on analytics projects using SQL, Python, Power BI and Excel.

## CrediTrack: Credit Card Default Risk Analysis
**SQL · T-SQL · Power BI · DAX · EDA**

- Analyzed 30,000 credit card customer records in SQL using CASE logic, aggregate functions and grouped queries to compare default rates across demographics, credit limits, repayment history and payment behavior.
- Built a six-page interactive Power BI dashboard with DAX measures and five slicers (age, education, marital status, credit limit, gender) to track KPIs such as default rate, repayment delay and payment-to-bill ratio.
- Found a 22.12% overall default rate; customers with severe repayment delays defaulted at about 70% versus 14% for on-time payers, and customers with credit limits below 50K defaulted at 36.07%.
- Found that defaulters paid nearly half as much as non-defaulters (3.40K vs 6.31K average); recommended early-warning alerts at the first repayment delay and review of accounts with payment-to-bill ratios of 10% or less.

[GitHub Repository](https://github.com/kar4mveer/CrediTrack-Credit-Card-Default-Risk-Analysis) · [README](https://github.com/kar4mveer/CrediTrack-Credit-Card-Default-Risk-Analysis#readme)

---

## Jaipur360: Tourism & Hospitality Analytics
**SQL · T-SQL · Power BI · DAX · Data Modeling**

- Cleaned and analyzed data on 254 hotels, 71 attractions and 137K reviews in SQL, using CASE-based price segments, JOINs, CTEs and window functions to rank hotels by price and review volume.
- Built a three-page interactive Power BI dashboard on a relational data model, with DAX-based KPI cards, slicers and maps for hotel budget exploration and attraction distribution.
- Found that religious (23.94%) and scenic (22.54%) attractions make up about 46% of Jaipur's 71 attractions, with most concentrated around central Jaipur.
- Identified ITC Rajputana as the most-reviewed hotel (about 6.2K reviews) and observed extreme price outliers, with the top hotel averaging INR 1,12,365 against a dataset average of INR 2.98K.

[GitHub Repository](https://github.com/kar4mveer/Jaipur360-Tourism-Analytics) · [README](https://github.com/kar4mveer/Jaipur360-Tourism-Analytics#readme)

---

## Retail Sales EDA & Business Insights
**SQL · T-SQL · Window Functions · CTEs · Data Warehouse**

- Performed end-to-end EDA on a star-schema data warehouse in SQL, analyzing $29.3M in revenue across 27,659 orders, 18,484 customers and 295 products.
- Wrote 28 T-SQL queries using JOINs, CTEs, subqueries and window functions (ROW_NUMBER, DENSE_RANK), and profiled the schema with INFORMATION_SCHEMA; consolidated all headline KPIs into a single UNION ALL query.
- Found revenue concentrated in one product family: the top five products were all Mountain-200 variants, generating about $6.7M (22.7% of revenue), while the top 10 customers contributed under 0.5%, showing product risk rather than customer risk.
- Recommended tracking Mountain-200 demand over time to separate seasonal peaks from structural dependency before diversifying; flagged unmapped "n/a" country values as a data-quality issue to clean.

[GitHub Repository](https://github.com/kar4mveer/Moto-Sales-EDA) · [README](https://github.com/kar4mveer/Moto-Sales-EDA#readme)

---

## E-Commerce Sales Dashboard
**Power BI · Power Query · DAX · Data Modeling**

- Built an interactive Power BI dashboard on e-commerce order data, using Power Query for cleaning and DAX for measures and KPIs.
- Tracked total quantity sold, total profit, monthly profit trends, state-wise sales, category-wise profit, top customers and payment-mode mix (COD, UPI, debit card, credit card, EMI).
- Added quarter and state slicers with cross-filtering, plus Q1 to Q4 analysis views for comparing performance across the year.

[GitHub Repository](https://github.com/kar4mveer/Ecommerce-Sales-Dashboard) · [README](https://github.com/kar4mveer/Ecommerce-Sales-Dashboard#readme)
