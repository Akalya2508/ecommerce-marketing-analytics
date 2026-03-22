# 📁 Data

## About the Dataset

This project uses an **E-Commerce Marketplace dataset** provided by **AnalytixLabs**
as part of the Marketing Analytics Capstone Project.

The data covers the period **September 2016 – October 2018** and contains
approximately **570,000 rows** across 8 tables.

---

## ⚠️ Data Not Included

The CSV files are **not included** in this repository due to copyright restrictions.

> *"This material is protected under copyright act AnalytixLabs© 2011–2020.
> Unauthorized use and/or duplication of this material or any part of this
> material without explicit and written permission from AnalytixLabs is
> strictly prohibited."*

To obtain the dataset, contact AnalytixLabs:
- 🌐 Website : www.analytixlabs.co.in


---

## 🗂️ Table Overview

| File | Rows | Description |
|---|---|---|
| `CUSTOMERS.csv` | 99,441 | Customer ID, city, state, zip code |
| `ORDERS.csv` | 99,441 | Order ID, status, purchase & delivery timestamps |
| `ORDER_ITEMS.csv` | 112,650 | Product ID, seller ID, price, freight per order line |
| `ORDER_PAYMENTS.csv` | 103,886 | Payment type, installments, payment value |
| `ORDER_REVIEW_RATINGS.csv` | 100,000 | Review score (1–5) per order |
| `PRODUCTS.csv` | 32,951 | Product ID, category, dimensions, weight |
| `SELLERS.csv` | 3,095 | Seller ID, city, state, zip code |
| `GEO_LOCATION.csv` | 19,015 | Zip code, latitude, longitude, city, state |

---

## 🔗 Data Model

```
ORDER_PAYMENTS          PRODUCTS
      |                     |
   order_id            product_id
      |                     |
      └──────► ORDERS ◄─────┘
               ORDER_ITEMS ◄──── seller_id ──► SELLERS
                   |                                |
              customer_id                   zip_code_prefix
                   |                                |
              CUSTOMERS ◄──── zip_code_prefix ──► GEO_LOCATION
                   |
         ORDER_REVIEW_RATINGS
```

---

## ▶️ How to Use

1. Obtain the CSV files from AnalytixLabs
2. Place all 8 CSV files in this `data/` folder
3. Open `Marketing_Analytics_Capstone.ipynb`
4. Update `DATA_DIR = './data/'` in Cell 2
5. Run All Cells
