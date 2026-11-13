# BlueMart Retail Analytics
An end-to-end retail analytics project that analyzes sales, profit, products, stores, channels and inventory for **BlueMart**, with an executive dashboard summarizing the key findings.

## Project Overview

- **Sales period:** Jan 2021 to Oct 2025
- **Inventory snapshot:** 31 Oct 2025
- **Scope:** 50 stores, 200 products (SKUs), 7 categories, 3 cities (Dubai, Abu Dhabi, Sharjah)
- **Transactions analyzed:** 641,798 sales lines

## Dashboard Preview

![Dashboard Overview](images/dashboard_overview.png)

![Key Insights](images/dashboard_insights_1.png)

![More Insights](images/dashboard_insights_2.png)

## Key Metrics

| Metric | Value |
|---|---|
| Total Sales | 73.2M |
| Total Profit | 21.1M |
| Profit Margin | 28.8% |
| Average Sale | 114 per transaction |
| Average Profit | 33 per transaction |

## Key Insights

- **Seasonality:** Sales peak in January/February each year and dip in September/October.
- **Categories:** Electronics leads with 55.7% of sales and 56.2% of profit.
- **Products:** Batteries, Cables, Chargers and Mobile Accessories are the four most profitable product groups. Batteries alone account for 18.8% of profit.
- **Cities:** Dubai contributes about 56.1% of total sales, followed by Abu Dhabi and Sharjah.
- **Stores:** Sales are spread evenly across stores (each between 1.43M and 1.50M).
- **Channels:** Stores are the largest channel (41.3%). Website, MobileApp, Amazon.ae and Noon together bring 58.7%.
- **Inventory:** 2,098 store-product combinations (24.0%) have high sales but low stock, though none are below their reorder point.

## Project Structure

```
bluemart-retail-analytics/
├── notebooks/    # Jupyter notebook with the full analysis
├── dashboard/    # Executive dashboard
├── prompts/      # Prompt used to build the analysis
├── images/       # Dashboard screenshots
├── data/         # Data notes
└── README.md
```

## 🛠️ Tech Stack
- **Data Analysis:** Python, Pandas, NumPy
- **Visualization:** Plotly, Matplotlib 
- **Environment:** Jupyter Notebook
- **Dashboard & AI:**  built with Claude AI


## Author
Abhisht pandey
