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

### 1. Customer Segments
- **74%** of transactions are from **Low** and **Medium** tier customers.
- High-tier customers are fewer but may yield higher margins per sale.
- Age distribution skews to **31–40 years**; gender split is nearly **50/50**.
- **Implication**: Retaining Low/Medium tier customers and upselling them can boost volume, while high-tier shoppers offer premium opportunities.

### 2. Product Profitability
- **Phones**: Over **50%** of revenue but only **14%** of total profit → thin margins.
- **Accessories**: ~**34%** of revenue, **42%** of profit → highest-margin category.
- **Clothing**: Lowest performer in both revenue and profit.
- **Implication**: Optimise pricing and supplier negotiations for Phones; prioritise Accessories for promotions and inventory.

### 3. Geography
- Sales concentrated in **Lagos, Abuja, and Abia** (over 50% of transactions).
- Other states contribute significantly less.
- **Implication**: Focus marketing/logistics on top states; approach underperforming states cautiously.

### 4. Profitability
- **86%** of transactions are profitable; **14%** result in losses.
- Losses may stem from returns, pricing errors, or promotions.
- **Implication**: Investigate and address recurring loss drivers.

### 5. Seasonality
- 2015: Low early-year profits, mid-year surge.
- 2016: Stronger overall performance, slight decline toward year-end.
- **Implication**: Plan marketing campaigns around mid-year peaks; adjust inventory to meet seasonal demand.
---

The analysis leveraged **Python**, **Pandas**, **Seaborn**, and **Matplotlib** to uncover trends, relationships, and performance drivers.

---

## Recommendations

1. **Boost High-Margin Lines**  
   Increase marketing and ensure stock availability for high-profit accessories.

2. **Optimise Phone Sales**  
   Review pricing and supplier terms; cross-sell accessories to raise order profitability.

3. **Target Customer Segments**  
   Implement loyalty programmes for Low/Medium tiers and tailor promotions by age group.

4. **Focus on Top Regions**  
   Allocate more resources to Lagos, Abuja, and Abia; explore partnerships in high-demand regions.

5. **Leverage Seasonal Trends**  
   Align promotions with peak demand months; manage inventory to avoid stockouts.


---

## Conclusion
By applying structured EDA, Dune can use these findings to:
- Increase profit margins  
- Strengthen customer retention  
- Optimise regional and seasonal strategies  


## Tools & Libraries
- Python  
- Pandas  
- Seaborn  
- Matplotlib  

## Repository Structure

dune-sales-analysis
├── Dune Sales Data.csv
├── Dune Sales Analysis.ipynb
├── README.md
