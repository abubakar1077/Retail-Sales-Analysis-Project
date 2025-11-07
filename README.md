# Retail Sales Analysis Project

**Goal:** Analyze the sales performance of an online retail store.

**Main questions:**
1. What is our overall revenue and profit?
2. How do sales evolve over time (by month, weekday)?
3. Which product categories, regions, and customers generate the most revenue?
4. Where are we losing money (low profit / high discount)?

**Tools:** Python, pandas, numpy, matplotlib, seaborn

This notebook is structured as:
1. Setup & Data Generation
2. Initial Exploration (EDA)
3. Data Cleaning & Feature Engineering
4. Business Questions & Visualizations
5. Insights & Conclusions
# Key Insights & Conclusions

Based on the synthetic retail data:

1. **Overall Performance**
   - Total net sales and total profit show that the business is (hypothetically) profitable.
   - The average order value and average discount levels indicate customers buy mid- to high-priced items with moderate discounts.

2. **Time Trends**
   - Monthly net sales and profit plots highlight peaks and troughs across the year.
   - These peaks could correspond to seasonal campaigns or holidays (e.g., end-of-year spike).

3. **Regional & Category Performance**
   - Some regions generate higher net sales and profit than others.
   - Certain product categories (e.g., Electronics) tend to dominate total revenue.
   - Management could focus marketing and inventory planning on high-performing categories and regions.

4. **Customer Concentration**
   - A small group of top customers contributes a significant share of revenue.
   - These customers could be targeted with loyalty programs or personalized offers.

5. **Discounts & Profitability**
   - The scatter plot suggests that very high discounts may hurt profit per order.
   - The company should test optimal discount levels that increase sales without destroying margins.

6. **Weekday Patterns**
   - Some weekdays have noticeably higher order volume and revenue.
   - This can guide staffing decisions, promotions, and campaign timing.

---
- **Time-series forecasting** of monthly sales,
- Or **customer segmentation** using clustering.
