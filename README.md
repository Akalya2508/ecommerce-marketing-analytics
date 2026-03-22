# 📊 E-Commerce Marketing Analytics

An end-to-end **Marketing Analytics** project on an Indian e-commerce marketplace
dataset covering **September 2016 – October 2018**, built as part of the
AnalytixLabs Data Analytics Capstone.

---

## 🎯 Objective

Help the business measure, manage, and analyse performance by generating
data-driven insights across customers, products, sellers, payments, and
customer satisfaction.

---

## 📌 Key Findings

| Metric | Value |
|---|---|
| 💰 Total Revenue | ₹2 Crore+ |
| 🛒 Total Orders | 97,899 |
| 👤 Unique Customers | 97,899 |
| 📦 Unique Products | 32,547 |
| 🏷️ Categories | 72 |
| 🏪 Sellers | 2,986 |
| ⭐ Avg Customer Rating | 4.0 / 5.0 |
| 📅 Peak Order Day | Monday |
| 🕐 Peak Order Hour | 4:00 PM |
| 🏆 Top Revenue Category | Bed Bath & Table |
| 📍 Top State by Revenue | Andhra Pradesh |
| 👑 Champion Customers (RFM) | 24,447 |

---

## 🔍 Analysis Covered

| # | Section | Description |
|---|---|---|
| 1 | **Data Loading & Cleaning** | 8-table join, null handling, datetime parsing |
| 2 | **High-Level KPIs** | Revenue, orders, customers, sellers, categories |
| 3 | **Customer Acquisition** | New customers acquired per month |
| 4 | **Retention Cohort Analysis** | Month-on-month retention heatmap |
| 5 | **New vs Existing Revenue** | Monthly revenue split by customer type |
| 6 | **Revenue Trends & Seasonality** | By month, day of week, hour of day |
| 7 | **Product & Category Analysis** | Top products, expensive items, category heatmap |
| 8 | **Geo-Location Analysis** | Revenue & orders by state and city |
| 9 | **RFM Segmentation** | 8 customer segments + seller revenue tiers |
| 10 | **Cross-Selling Analysis** | Top product pairs & triplets bought together |
| 11 | **Payment Behaviour** | Payment type distribution, installment usage |
| 12 | **Customer Satisfaction** | Ratings by category, state, seller, month |

---

## 🗂️ Repository Structure

```
ecommerce-marketing-analytics/
├── 📓 Marketing_Analytics_Capstone.ipynb   ← main notebook
├── 📄 requirements.txt                     ← Python dependencies
├── 📄 .gitignore                           ← ignores CSVs & checkpoints
├── 📄 README.md                            ← you are here
└── 📁 data/
    └── README.md                           ← dataset info & how to obtain
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.9+ | Core language |
| Pandas | Data manipulation & joins |
| NumPy | Numerical operations |
| Matplotlib | Charts & visualisations |
| Seaborn | Statistical plots & heatmaps |
| Scikit-learn | RFM scoring (quantile cuts) |
| Jupyter Notebook | Interactive development |

---

## ▶️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/ecommerce-marketing-analytics.git
cd ecommerce-marketing-analytics
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Add the dataset**

Place all 8 CSV files inside the `data/` folder.
See `data/README.md` for how to obtain the dataset.

**4. Open the notebook**
```bash
jupyter notebook Marketing_Analytics_Capstone.ipynb
```

**5. Update the data path**

In Cell 2, change:
```python
DATA_DIR = './data/'
```

**6. Run All Cells**

`Kernel` → `Restart & Run All`

---

## 📁 Dataset

Dataset provided by **AnalytixLabs** as part of the Marketing Analytics Capstone.
Not included in this repository due to copyright restrictions.

> Visit [www.analytixlabs.co.in](https://www.analytixlabs.co.in) for details.

---

## 👤 Author

**Akalya Balasubramaniyan**
- 🔗 LinkedIn: linkedin.com/in/your-profile
- 📧 Email: akalyaa116@gmail.com
- 🐙 GitHub: github.com/Akalya2508

---

## 📜 License

This project (code & analysis) is open source under the [MIT License](LICENSE).
The dataset is copyright © AnalytixLabs 2011–2020 and is not covered by this license.
