📊 Retail Business Analytics Report | Power BI

An interactive 3-page Power BI dashboard that turns retail transaction data into clear insights on sales, profit, and customer behavior.

🎯 Objective
To analyze retail performance and answer key business questions:
- How are sales and profit growing compared to last year?
- Which categories, segments, and countries drive the most revenue?
- Who are the most valuable customers?
- How does order priority affect profit?

🖼️ Dashboard Preview

| Sales | Profit | Demographics |
|-------|--------|--------------|
| ![Sales](screenshots/sales.png) | ![Profit](screenshots/profit.png) | ![Demographics](screenshots/demographics.png) |

📑 Dashboard Pages

1. Sales
- KPIs: Total Sales, Total Sales LY, YoY Sales %, Avg Sales per Order
- Sales by Category and Segment
- Top 5 selling products by year (2011 to 2014)
- Monthly sales comparison vs last year
- Sales by Country (treemap)

2. Profit
- KPIs: Total Profit, Total Profit LY, YoY Profit %, Avg Profit per Order
- Profit by Category and Segment
- Top 5 products by profit
- Monthly profit comparison vs last year

3. Demographics
- KPIs: Total Customers, Total Orders, Total Products, Avg Sales per State
- Top 10 valuable customers and quantity by customer
- Top-ranked states (dynamic Top N slider)
- Profit by Order Priority and by Region

📌 Key Insights
- **Total Sales:** $12.64M, up **51.54%** YoY
- **Total Profit:** $1.47M, up **52.34%** YoY
- **Technology** is the top category in both sales ($4.74M) and profit
- **Furniture** ranks 2nd in sales but lowest in profit, which suggests a margin issue
- **Consumer** segment contributes about 51% of sales and profit
- **United States** is the top-selling country
- **Medium priority** orders generate the highest profit ($864.2K)
- Profit and sales dip every **July** and peak in **Q4**

🛠️ Tools & Skills
- **Power BI Desktop**
- **DAX** (YoY calculations, previous-year measures, KPIs)
- Data modeling and data cleaning
- Interactive design: slicers (Date, Country), page navigation buttons, Top N parameter
- Visuals: KPI cards, donut, bar, line, treemap, ribbon charts

📂 Repository Structure
```
├── Retail_Business_Analytics.pbix
├── screenshots/
│   ├── sales.png
│   ├── profit.png
│   └── demographics.png
├── data/                # dataset (add source/link here)
└── README.md
```

🚀 How to Use
1. Download the `.pbix` file from this repo.
2. Open it in **Power BI Desktop**.
3. Use the **Date** and **Country** slicers and the **Sales / Profit / Demographics** buttons to explore.


👩‍💻 Author
Avanthika Shibu
Aspiring Data Analyst
🔗 LinkedIn:www.linkedin.com/in/avanthika-shibu05

⭐ If you found this useful, feel free to star the repo and share your feedback!
