# superstore-sales-analysis
A Python-based exploratory data analysis (EDA) of the Sample Superstore dataset, examining revenue, profit, regional performance, and customer segmentation across 9,994 orders from 2014–2017.

---

## Project Structure

```
superstore-sales-analysis/
│
├── Superstore_Sales_Analysis.ipynb   # Main analysis notebook
├── Sample_-_Superstore.csv           # Dataset (Kaggle)
└── README.md                         # This file
```

---

##  How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `Superstore_Sales_Analysis.ipynb`
3. Run Cell 1 and upload `Sample_-_Superstore.csv` (which is included) when prompted
4. Run all remaining cells in order (Runtime → Run All)

---

##  Dataset

**Sample Superstore Sales Dataset** — available free on [Kaggle](https://www.kaggle.com/)

- 9,994 rows × 21 columns
- Covers orders from 2014–2017
- Includes order details, customer info, geography, product categories, sales, profit, and discounts

## Project Overview

---

This project answers four core business questions a data analyst would face with a retail dataset:

1. **How is the business performing overall?** — Revenue, profit, margin, and growth trends
2. **Which products are driving the business?** — Category and sub-category profitability
3. **Where is the business strongest?** — Regional and state-level performance
4. **Who are the most valuable customers?** — Segment analysis and top customer identification

---

##  Key Findings

| Metric | Value |
|---|---|
| Total Revenue | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Profit Margin | 12.5% |
| Total Orders | 5,009 |
| Total Customers | 793 |

- 📉 **Profit margin (12.5%) sits below the healthy 10–20% retail benchmark**
- 📅 **February is consistently the lowest revenue month** across all years; Q4 is the strongest
- 🛍️ **Technology leads with 17.4% margin**; Furniture lags at just 2.5%
- 🪑 **Tables is the single biggest profit drain** at -$17,725 total profit
- 🗺️ **The West region outperforms** at 14.9% margin; Central is the weakest at 7.9%
- 👥 **Home Office is the most profitable segment** at 14.0% margin
- ⚠️ **Heavy discounts are destroying margin** — orders with 40%+ discounts average **-$106.71 profit** vs +$67.46 for lightly discounted orders

---

## Recommendations

1. **Cap discounts at 20%** — the data shows a clear and steep drop in profit beyond this threshold
2. **Review Tables pricing strategy** — the sub-category is consistently unprofitable
3. **Investigate Central region operations** — lowest margin and likely over-discounting
4. **Launch a February promotional campaign** — offset the seasonal revenue dip
5. **Study West region practices** — apply what's working there to underperforming regions

---

## Tools & Libraries

- **Python** — core language
- **pandas** — data manipulation and aggregation
- **numpy** — numerical operations
- **matplotlib / seaborn** — static visualizations
- **plotly** — interactive charts and choropleth maps
- **Google Colab** — development environment

---


