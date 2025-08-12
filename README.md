# Dune-Sales-Analysis-An-Exploratory-Analysis-with-Python
Dune, an online retail company, needs to understand its sales performance and customer behavior to improve revenues and profitability. The core questions are: Which product and customer segments drive the most sales and profit? How does performance vary by time and geography? Answering these will help executives refine strategy and boost growth.

# Dune E-Commerce Sales Analysis – Exploratory Data Analysis (EDA)

**Case Study: Retail Sales Analysis for Strategic Insights**

---

## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) for **Dune**, an online retail company in Nigeria. With over 34,000 sales transactions, this case study answers key business questions about revenue performance, customer segmentation, product profitability, regional demand, and seasonal trends.

The analysis was executed using Python libraries **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**, transforming raw transaction data into actionable insights for executive decision-making.

---

## Business Context

Dune operates in a competitive e-commerce environment, selling electronics and apparel. Executives needed a data-driven view into:

- Which product categories and customer segments are most profitable?
- What regions and time periods drive or limit performance?
- Where do losses occur, and how can they be minimised?

These insights inform decisions in marketing, inventory, and customer engagement strategies.

---

## Objectives

1. Profile customer segments by tier, age, and gender.
2. Identify high-performing and low-performing product categories.
3. Map sales and profit distribution across Nigerian states.
4. Understand seasonality and monthly performance patterns.
5. Recommend strategies to optimise marketing, pricing, and inventory.

---

## Dataset Summary

| Feature | Description |
|---------|-------------|
| Date | Transaction date |
| Customer | Tier (High, Medium, Low) |
| Sales_Person | Assigned sales staff |
| Customer_Age / Gender | Demographic attributes |
| State | Geographic sales location |
| Product_Category / Sub_Category | Electronics and clothing segments |
| Payment_Method | Mode of payment |
| Quantity / Unit_Cost / Unit_Price | Transaction metrics |
| Derived Features | Age group, cost, revenue, profit, profit label, year, month, quarter |

---

## Methodology

### Data Cleaning
- Removed rows with extensive missing values.
- Corrected typos in categorical fields (e.g., “Hign” ➜ “High”).
- Converted `Date` to datetime and extracted year, month, and quarter.
- Engineered financial metrics: `cost`, `revenue`, and `profit`.

### Exploratory Analysis
- Profiled customer tiers, gender splits, and age groups.
- Summarised revenue and profit by product category and subcategory.
- Assessed state-level sales concentration.
- Measured transaction-level profitability (86% profitable, 14% loss-making).
- Tracked monthly profit trends to identify seasonal patterns.

### Visualisation
- Count plots for customer tiers and demographics.
- Bar charts for state and category performance.
- Pie charts for Profit vs. Loss transactions.
- Line plots for monthly profit trends.
- Correlation heatmaps for numeric features.

---

## Key Findings

**Customer Segments**
- Low and Medium tier customers account for ~74% of transactions.
- High-tier customers, though fewer, may yield higher profit per order.
- Age group 31–40 dominates; gender split is nearly even.

**Product Profitability**
- Phones generate over 50% of total revenue but just ~14% of profit.
- Accessories contribute ~34% of revenue but ~42% of profit, making them the highest-margin category.
- Clothing underperforms in both revenue and profit.

**Geographic Insights**
- Lagos, Abuja, and Abia account for over half of all transactions.
- Indicates opportunity to focus marketing and logistics on top-performing regions.

**Seasonal Trends**
- 2015 saw low early-year profits with mid-year spikes.
- 2016 showed stronger performance overall, peaking mid-year.

---

## Recommendations

1. **Prioritise Accessories**: Increase promotions and ensure adequate inventory for high-margin items.
2. **Optimise Phone Sales**: Negotiate better supplier costs or adjust pricing; bundle with accessories.
3. **Target Low/Medium Tiers**: Loyalty programmes could increase repeat purchases.
4. **Focus on Top States**: Concentrate resources on Lagos, Abuja, and Abia.
5. **Plan Around Seasonality**: Align campaigns with historical demand peaks.

---

## Future Enhancements

- Drill into product subcategories for more targeted strategies.
- Apply clustering to develop data-driven customer personas.
- Conduct A/B testing for regional or segment-specific promotions.
- Build real-time dashboards in Power BI or Tableau.

---

## Personal Reflection

As a Yoruba-born analyst working within the UK data landscape, I bridge cultural context and commercial insight. This project demonstrates my ability to combine storytelling with technical rigour, delivering clear, actionable insights grounded in robust statistical analysis.

---

## Repository Structure

dune-sales-analysis
├── Dune Sales Data.csv
├── Dune Sales Analysis.ipynb
├── README.md
