# E-Commerce Sales Performance Dashboard

An interactive one-page Power BI dashboard analyzing a multi-year global e-commerce sales dataset (2021-2024, 10K+ orders) to surface revenue, profit, and operational insights across regions, categories, and customer segments.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1CADE4?style=flat)

## Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

*(Replace `dashboard_preview.png` with an exported screenshot of the final dashboard.)*

## Dataset

- **Source:** [Global E-Commerce Sales Dataset 2021-2024](https://www.kaggle.com/datasets/abdelfattahibrahim/global-e-commerce-sales-dataset-20212024) (Kaggle)
- **Size:** ~10,000 orders
- **Period:** 2021-2024
- **Key fields:** Order date, revenue, profit, cost, category, sub-category, product name, customer segment, region, country, payment method, shipping method, shipping days, order status

## Objective

The goal of this project was to design a single-page executive dashboard that answers key business questions at a glance:

- How are revenue and profit trending over time?
- Which product categories and regions drive the most revenue and profit?
- How healthy is order fulfillment, and how significant is the return/cancellation problem?
- Which customer segments and payment methods contribute most to revenue?

## Dashboard Components

**KPI Cards**
- Total Revenue
- Total Profit
- Profit Margin (%)
- Total Orders
- Return/Cancellation Rate (%)
- Average Order Value

**Visualizations**
- Revenue and profit trend by month
- Revenue by region (donut chart)
- Revenue and profit by category (clustered bar)
- Top 5 revenue by country (bar chart)
- Top 5 revenue by product name (bar chart)
- Orders by category and order status (stacked bar)
- Revenue by customer segment (pie chart)
- Revenue by payment method (bar chart)

**Interactivity**
- Year slicer
- Shipping method slicer
- Cross-filtering across all visuals

## Key Insight

The dashboard highlighted a **27.7% return/cancellation rate**, identifying this as a key area for operational improvement and a priority for further root-cause analysis (e.g., by category, region, or shipping method).

## Tools & Techniques

- **Power BI Desktop** for data modeling, visualization, and report design
- **DAX** for calculated measures (Total Revenue, Total Profit, Profit Margin, Return/Cancellation Rate, Average Order Value)
- **Power Query** for data cleaning and transformation
- Custom Power BI theme for consistent color usage across all visuals
- Single-page layout design optimized for executive-level readability

## Repository Contents

```
├── ecommerce_sales_dataset.csv     # Source dataset
├── ecommerce_dashboard.pbix        # Power BI report file
├── ecommerce_dashboard_theme.json  # Custom Power BI theme
└── README.md
```

## How to Use

1. Clone this repository.
2. Open `ecommerce_dashboard.pbix` in Power BI Desktop.
3. (Optional) Apply the custom theme via **View > Themes > Browse for themes** and select `ecommerce_dashboard_theme.json`.
4. Use the Year and Shipping Method slicers to explore the data interactively.

## Author

Mukti

## License

This project uses a dataset sourced from Kaggle for educational and portfolio purposes.
