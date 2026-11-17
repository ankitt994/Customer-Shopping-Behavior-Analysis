# Project scope, deliverables and analytical boundaries

## Business problem

A retail company wants to better understand customer shopping behaviour to improve sales, customer satisfaction and long-term loyalty. The analysis is intended to explore differences across customer demographics, product categories and purchase preferences, including discounts, reviews, seasons and payment methods.

**Overarching business question:** How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

## Deliverables checklist

- [x] **Python — Data preparation:** Existing Python analysis document covers cleaning, missing-value treatment, feature engineering and preparation for SQL analysis.
- [x] **SQL — Business analysis:** Existing MySQL script contains ten business questions covering revenue, discounts, ratings, shipping, subscriptions, customer segments, products and age groups.
- [x] **Power BI — Visualization:** A PBIX dashboard is present in the repository.
- [x] **Presentation:** A PowerPoint presentation is present.
- [x] **Supporting report/review:** A project review PDF and Python analysis PDF are present.
- [x] **GitHub repository:** The project files are stored in this repository.

The check marks indicate that a corresponding file is present in the repository. They do not represent an independent audit of every calculation, visual or conclusion.

## Dataset coverage

The project documentation describes 3,900 records and 18 attributes, including customer demographics, product/category, purchase amount, season, review rating, subscription status, shipping type, discount/promo-code usage, previous purchases and payment method.

## Important analytical boundaries

The problem statement mentions online/offline channels, campaigns/CRM and repeat purchases. The documented dataset fields do not include an explicit sales channel, campaign exposure or dated customer transaction history. Consequently, those questions cannot be directly answered with the current fields.

- Use previous-purchase count as a customer-history indicator, not as a fully measured repeat-purchase rate.
- Do not infer campaign effectiveness without campaign exposure and outcome data.
- Do not infer online/offline channel performance without a channel field.
- Do not claim that discounts or subscriptions cause higher spend from descriptive comparisons.
- Do not make profitability claims without cost or margin data.

## Suggested extensions

If the business later provides channel, campaign, transaction-date and cost data, extend the analysis to channel mix, campaign lift, cohort retention, purchase intervals, customer lifetime value and discount profitability.
