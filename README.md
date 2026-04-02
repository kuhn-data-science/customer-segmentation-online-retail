# 🛍️ Online Retail Customer Segmentation (RFM Analysis)

This project performs an exploratory analysis and customer segmentation on the famous UCI Online Retail dataset using the **Recency-Frequency-Monetary (RFM)** framework.

## 📊 Project Overview

The goal of this project was to understand customer purchasing behavior and identify high-value customer segments for a UK-based online gift retailer.  
Using transactional data from 2010–2011, customers were segmented based on their recency, frequency, and monetary value. The analysis reveals a strong Pareto effect in customer value distribution.

- **Dataset**: UCI Online Retail Dataset (541,909 transactions)
- **Unique Customers**: 4,338
- **Methods**: RFM Analysis, Quintile Scoring, Rule-based Segmentation
- **Key Insight**: 28% of customers generate 73% of total revenue

## 🎯 Research Focus

- Calculate and interpret RFM metrics for each customer
- Transform RFM scores into meaningful business segments (Champions, Loyal Customers, At Risk, Lost, etc.)
- Analyze the distribution of customer value and identify a Pareto-like pattern
- Examine intercorrelations between Recency, Frequency, and Monetary

## 🧠 Key Findings

- **Champions** and **Loyal Customers** (only 28% of all customers) account for **73.3%** of total revenue (£6.53M out of £8.91M).
- A large group of **Lost Customers** (19%) contributes only 2.1% of revenue.
- Strong positive correlation between Frequency and Monetary value (Spearman’s ρ = 0.81).
- Clear right-skewed distributions in all three RFM dimensions.


## 💾 Data Source

**Dataset:**  
Chen, D. (2015). *Online Retail* [Data set]. UCI Machine Learning Repository.  
https://doi.org/10.24432/C5BW33

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## 👤 Author

Moritz Konstantin Kuhn  
Data Science & Communication Research  
📧 moritzk.kuhn@gmx.com  
🔗 [LinkedIn](https://www.linkedin.com/in/moritz-konstantin-kuhn)
