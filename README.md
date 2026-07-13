# Marketplace Funnel Analysis

End-to-end exploratory data analysis of 99,441 real e-commerce orders 
using Python and SQL, based on the Olist Brazilian E-Commerce dataset.

---

## Project Overview

This project analyzes the complete order funnel of an e-commerce marketplace — 
from order placement to delivery — to identify drop-offs, revenue patterns, 
and delivery performance insights.

---

## Business Questions Answered

- How efficiently do orders move through each funnel stage?
- Which payment methods drive the most revenue?
- What is the average delivery time and are there outliers?
- When do customers place the most orders (hour and day patterns)?
- Where are the conversion leaks in the funnel?

---

## Key Findings

| Metric | Value |
|---|---|
| Total Orders | 99,441 |
| Delivery Rate | 97.0% |
| Cancellation Rate | 0.6% |
| Payment Conversion | 98.9% |
| Avg Delivery Time | 12.6 days |
| Top Payment Method | Credit Card (77% of revenue) |

---

## Business Insights

1. **Highly efficient funnel** — 97% delivery rate with only 0.6% cancellations
2. **Perfect payment conversion** — 98.9% of placed orders complete payment
3. **Credit card dominates** — BRL 12.5M revenue across 76,795 transactions
4. **Voucher opportunity** — avg order value BRL 65.70 vs BRL 163.32 for credit card
5. **775 incomplete orders** — gap between orders placed and items attached
6. **Delivery outliers** — max delivery of 209 days needs operational attention

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Data processing and analysis |
| pandas | Data manipulation |
| SQLite | Structured queries on order data |
| seaborn | Static visualizations |
| matplotlib | Chart customization |
| Jupyter Notebook | Analysis environment |

---



