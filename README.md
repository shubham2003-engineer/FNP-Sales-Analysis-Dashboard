# FNP Sales Analysis Dashboard

An interactive Excel dashboard that analyses order data from an e-commerce gifting business (FNP) to show what sells, when customers buy, and how fast orders are delivered.

<img width="1768" height="780" alt="Dashboard image (1)" src="https://github.com/user-attachments/assets/edfc7372-5a2d-4b87-8dcc-747b2a52b1c8" />

## Business Problem

An online gifting business sells across many occasions, categories, products and cities. Raw order data does not show which of these drive revenue, when customers order, or whether delivery keeps pace. This project turns that data into a single dashboard that supports business decisions.

## Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 149 |
| Total Revenue | ₹4,08,194 |
| Average Customer Spend (AOV) | ₹2,739.56 |
| Average Order-to-Delivery Time | 5.46 days |

## Key Insights

- **Colors** is the top revenue category (~39% of total revenue), with **Soft Toys** a distant second.
- Monthly revenue **peaks in April** and **drops sharply in November**.
- Revenue varies widely by **hour of the day**, so order timing matters.

## Recommendations

- Bundle top categories to lift average order value.
- Time offers and campaigns around peak months and order hours.
- Investigate the 5.46-day delivery time to speed up fulfilment.

## What I Did

1. Merged and cleaned three datasets: customers, orders and products.
2. Engineered new fields: order hour, order month and delivery time (order date to delivery date).
3. Built KPI cards and charts for revenue by occasion, category, hour, month, top products and top cities.
4. Added slicers and timelines (Occasion, Order Date, Delivery Date) for interactive filtering.

## Dashboard Views

- Revenue by Occasion
- Revenue by Category
- Revenue by Hour (Order Time)
- Revenue by Month
- Top 5 Products by Revenue
- Top 10 Cities by Order

## Repository Structure

```
FNP-Sales-Analysis-Dashboard/
├── Dashboard.xlsx        # Final interactive dashboard
├── Dashboard_image.png   # Dashboard screenshot
├── customers.csv         # Customer data
├── e_orders.csv          # Order data
├── products.csv          # Product data
└── README.md
```

## Tools Used

- Microsoft Excel (Pivot Tables, Charts, Slicers, Timelines)
- Data cleaning and KPI design

## How to Use

1. Download `Dashboard.xlsx`.
2. Open it in Microsoft Excel.
3. Use the Occasion slicer and the Order Date / Delivery Date timelines to filter the dashboard.

## Author

**Shubham Sahu**
[GitHub](https://github.com/shubham2003-engineer) | [LinkedIn](https://www.linkedin.com/in/shubham-sahu-7633bb220/?isSelfProfile=true)

Feedback and suggestions are welcome.
