# Customer Shopping Behavior Analysis

**End-to-end analytics project | Python • MySQL • Power BI**

This project explores customer shopping patterns in a retail dataset and demonstrates an analytics workflow from data preparation to business-facing insights.

- **Author:** Ankit Tripathi
- **Location:** Bengaluru, India
- **Dataset:** 3,900 purchase records and 18 attributes
- **Tools:** Python, Pandas, MySQL, Power BI, PowerPoint

---

## 1. Business problem

A retail business wants to understand how customer demographics, product preferences, discounts, reviews, seasons, payment methods and subscription status relate to shopping behaviour. The goal is to use these patterns to improve customer engagement, product decisions and marketing effectiveness.

**Guiding business question**

> How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

## 2. Project objectives

1. Prepare a reliable, analysis-ready dataset using Python.
2. Use MySQL to answer business questions about customer segments, spending, products and purchase drivers.
3. Present key metrics and patterns in an interactive Power BI dashboard.
4. Communicate findings and practical recommendations through project documentation and a presentation.
5. Keep the workflow, code and deliverables accessible in this repository.

## 3. Dataset overview

The analysis uses 3,900 shopping records with 18 fields. The available attributes cover:

- **Customer profile:** age, gender, location
- **Purchase information:** item purchased, category, purchase amount, season
- **Shopping behaviour:** previous purchases, purchase frequency, subscription status
- **Purchase experience:** review rating, shipping type
- **Purchase preferences:** discount and promo-code usage, payment method, size and colour

### Data preparation

The Python workflow documents handling of missing review ratings, standardization of column names, feature engineering (including age groups and purchase-frequency fields), and preparation of a clean dataset for SQL analysis. The existing analysis records 37 missing values in `review_rating`, imputed using the median review rating by product category.

## 4. Analysis workflow and deliverables

| Stage | Tool | Work / deliverable |
|---|---|---|
| Data preparation | Python / Pandas | Data cleaning, validation, feature engineering and prepared data |
| Business analysis | MySQL | SQL queries for revenue, discount usage, product ratings, shipping, subscriptions and customer segmentation |
| Visualization | Power BI | Interactive customer behaviour dashboard |
| Communication | PowerPoint / PDF | Presentation and supporting project review / analysis documents |
| Version control | GitHub | Project assets and documentation |

### Repository files

| File | Description |
|---|---|
| [Python analysis PDF](Customer_Shopping_Behavior_Analysis%28python%29.pdf) | Export of the Python data-preparation and analysis work |
| [MySQL queries](Customer_behavior_dashboard%28MySQL%29.sql) | SQL business questions and analysis queries |
| [Power BI dashboard](Customer_Behavior_Dashboard.pbix) | Download and open in Power BI Desktop |
| [Project presentation](Customer-Shopping-Behavior-Analysis.pptx) | Stakeholder presentation |
| [Project review](Project%20Review.pdf) | Supporting project review document |

> **Power BI note:** GitHub does not render PBIX files in the browser. Download the PBIX file and open it using Power BI Desktop.

## 5. Business questions explored in SQL

The current SQL analysis covers:

1. What is the revenue split between male and female customers?
2. Which customers used a discount but still spent at least the overall average?
3. Which products have the highest average review ratings?
4. How does average purchase amount differ between Standard and Express shipping?
5. How do average spend and total revenue compare for subscribers and non-subscribers?
6. Which products have the highest proportion of discounted purchases?
7. How many customers fall into New, Returning and Loyal groups based on previous-purchase counts?
8. What are the three most purchased products in each category?
9. How many repeat buyers (more than five previous purchases) are subscribers versus non-subscribers?
10. Which age groups contribute the most revenue?

## 6. Current insights documented in the project

The existing project notes report the following patterns:

- Subscribers show higher average order value and total revenue in the analyzed records.
- Discount usage is associated with purchases, but discount effectiveness should be assessed alongside margin data before changing promotional budgets.
- Customers with higher previous-purchase counts are an important segment for retention initiatives.
- Express shipping is associated with higher average purchase amounts in the analyzed records.

These are descriptive findings from this dataset, not proof that subscriptions, discounts or shipping options cause higher spending. Validate the underlying figures in the SQL outputs and dashboard before using them as business targets.

## 7. Recommendations to investigate

- Test targeted loyalty or retention offers for customers with higher previous-purchase counts.
- Compare discount rates and average order values by product category before allocating promotions.
- Evaluate subscription engagement and spending patterns to identify suitable audiences.
- Use product ratings and category-level demand to inform merchandising and product decisions.
- Review payment-method preferences when planning checkout and customer-experience improvements.

## 8. Dataset limitations and interpretation

The available dataset is a set of 3,900 purchase records with customer and purchase attributes. The fields documented in the project do **not** include an explicit online/offline channel, campaign exposure, customer-level transaction dates, profit or product cost.

Therefore:
- Online-versus-offline performance and campaign attribution cannot be measured from the documented fields.
- Previous-purchase count can be used as a repeat-purchase proxy, but a dated transaction history is needed for true repeat-rate, cohort and time-to-next-purchase analysis.
- Discount impact on profitability cannot be established without margin or cost data.
- Season can be compared as a recorded category, but the dataset does not by itself establish year-over-year seasonal trends.

These are useful extensions for a richer retail dataset, not results claimed by the current analysis.

## 9. Future enhancements

- Add channel, campaign, transaction-date and margin data to support channel and campaign effectiveness analysis.
- Build customer cohorts and time-based retention metrics when transaction-level history is available.
- Add customer lifetime value and profitability analysis when the required data is available.
- Automate data refresh and document the end-to-end pipeline.

---

## Connect

**Ankit Tripathi**  
[LinkedIn](https://www.linkedin.com/in/ankittripathiii/) · [GitHub](https://github.com/ankitt994)

*This repository is a portfolio project demonstrating data preparation, SQL analysis, dashboarding and business communication.*
