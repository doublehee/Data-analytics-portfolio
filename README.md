# Brazil E-Commerce Revenue & Sales Performance Analysis

> Power BI · Power Query · DAX · Data Modelling · 2026

---

## Overview

Multi-page interactive Power BI dashboard analyzing a Brazilian e-commerce dataset.
Covers $13.63M in revenue across 95,128 customers and 3 years of transaction data.

## Files in This Folder

| File | Description |
| Main Power BI dashboard file | `Brazil_Ecommerce_Executive_Summary.pptx` |
| `Brazil_ecommerce.pdf` | Dashboard export PDF |

## Data Cleaning Steps

1. **State abbreviations** — imported reference table, merged to replace SP/RJ/MG etc. with full names
2. **Portuguese categories** — imported translation table, merged to convert all category names to English
3. **Duplicate removal** — audited key columns for duplicate orders and customer records
4. **Data modelling** — linked all 6 tables (Customer, Fact, Order, Payment, Product, Seller) via relationships

## Dashboard Pages

### Page 1 — Revenue & Sales
- KPI cards: Total Revenue, Total Orders, Avg Order Value, Freight Cost
- Top 5 costliest products to ship (bar chart)
- Top 5 revenue-generating products (bar chart)
- Revenue by Month (line chart)
- Revenue by State (map)
- Filters: Payment Type, Year

### Page 2 — Logistics
- KPI cards: Items per Order, Avg Delivery Time, Churn Risk Value, Carrier→Customer Gap, Total Customers, Revenue
- Late vs Early Deliveries (donut chart)
- Top 7 products by order amount (bar chart)
- Filters: Payment Type, Year, Time Order Delivered, Product Category, Customer State

## Key Metrics

| Metric | Value |
| Total Revenue | $13.63M |
| Total Customers | 95,128 |
| YoY Revenue Growth | 20%+ (2017→2018) |
| Highest Avg Order Value | $236.18 (Voucher) |
| Early Deliveries | 91.9% |
| Carrier→Customer Gap | 9.28 days |
| Churn Risk Value | $165.59K |
| Items per Order | 1.19 avg |

## Tools Used

- Power BI Desktop
- Power Query (M Language)
- DAX
- Data Modelling (6 relational tables)
