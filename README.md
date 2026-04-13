# 📊 Online Retail Analysis (UK E-commerce Dataset)

## Project Overview

This project explores transactional data from a UK-based online retail company between 2010 and 2011.

The goal of the analysis is to understand revenue patterns, customer behavior, product performance, and return dynamics in order to generate business insights.

---

## Dataset Description

The dataset contains real transactional records, including:

* Invoice number
* Product (StockCode, Description)
* Quantity
* Invoice date
* Unit price
* Customer ID
* Country

Additional features were engineered to support analysis (e.g., revenue, transaction type, time-based features).

---

## Objectives

* Analyze overall revenue performance
* Identify top-performing products and customers
* Explore purchasing behavior patterns
* Evaluate return rates and return drivers
* Detect potential business issues and opportunities

---

## Data Cleaning & Preparation

* Removed non-relevant entries (e.g., postage-related transactions)
* Handled missing values in product descriptions
* Identified and excluded non-commercial records (e.g., adjustments, internal operations)
* Filtered returns to focus on actual revenue impact

---

## 📊 Key Analyses

### Revenue Analysis

* Monthly, daily, and hourly revenue trends
* Seasonality and peak sales periods

### Product Analysis

* Top products by revenue and quantity
* Price vs volume relationship
* Long-tail distribution of products

### Customer Analysis

* Revenue distribution across customers
* Average order value
* Customer purchasing behavior patterns

### Returns Analysis

* Return rate and financial impact
* Top products by return value
* Identification of non-commercial return entries
* Comparison of return-heavy vs high-performing products

---

## 🔍 Key Insights

* The business generated strong revenue (~$10.7M), with returns accounting for ~8.4%
* Revenue shows clear seasonality, peaking in November (pre-holiday period)
* A small number of products drive a large share of total revenue
* High-revenue products are not always high-volume products
* Customer behavior varies between frequent small purchases and infrequent high-value orders
* Returns are highly concentrated in a small subset of products rather than evenly distributed

---

## 💡 Business Recommendations

* Investigate high-return products for potential quality or expectation issues
* Focus on top-performing products to maximize revenue growth
* Consider strategies for high-value customers (retention or targeting)
* Monitor return-heavy items to reduce revenue loss

---

## 📈 Visualizations

Key visualizations are included in the notebook and the `images/` folder.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib

---

## Project Structure

```
online-retail-analysis/
│
├── analysis.ipynb
├── README.md
└── images/
```

---

## Author

Mariia Strykalo 
Aspiring Data Analyst  

- GitHub: https://github.com/Mariia-Strykalo/
- LinkedIn: https://www.linkedin.com/in/mariia-s-371483325/

This project was developed as part of a personal data analytics portfolio.
