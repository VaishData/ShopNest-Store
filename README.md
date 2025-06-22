# ShopNest Africa – Power BI Analytics App

Welcome to the **ShopNest Africa Power BI App**, a dynamic business intelligence solution designed to help you visualize and understand key performance metrics for ShopNest operations across the African region.

This app leverages real-time and historical data to empower decision-makers with actionable insights across sales, logistics, customer behavior, and product performance.

---

## 📌 Report Overview

| Report Page | Description | Key Questions Answered |
|-------------|-------------|--------------------------|
| **Top Categories by Total Price** | Displays top-performing product categories based on total revenue generated | - Which categories generate the most sales?<br>- What are their price contributions? |
| **Delayed Orders Analysis** | Identifies causes and trends in delayed deliveries | - What percentage of orders are delayed?<br>- What are the common delay reasons? |
| **Monthly Comparison: Delayed vs On-Time Orders** | Tracks delivery performance over time | - Are delivery timelines improving?<br>- How do months compare in terms of efficiency? |
| **Payment Method Analysis** | Examines how customers pay and how it affects revenue and refunds | - Which methods are most used in Africa?<br>- Is there a correlation with order issues? |
| **Product Rating Analysis** | Evaluates product quality perception and impact on sales | - Do better-rated products perform better?<br>- What is the rating distribution by category? |
| **State-wise Performance** | Analyzes regional sales and order volume | - Which African states contribute most to sales?<br>- Where is underperformance seen? |
| **Seasonal Sales Patterns** | Studies how seasons and events influence buying behavior | - Which months/seasons see a spike?<br>- How can we plan inventory better? |
| **Revenue Analysis** | Provides a deep dive into sales, profit, and influencing factors | - What are the major revenue drivers?<br>- Where are we gaining or losing margin? |

---

## 🗂 Data Sources

| Table | Description | Frequency |
|-------|-------------|-----------|
| `Orders_Africa` | Order details (status, date, price, region) | Daily |
| `Products` | Product info including ratings, categories, pricing | Weekly |
| `Customers_Africa` | Regional customer data, demographics, payment methods | Weekly |
| `Payments` | Transaction methods and refund status | Daily |

All data is sourced from ShopNest’s Africa-specific database hosted in **Azure Africa South**.

---

## 🧭 Navigation Tips

- **Use Filters**: Top-page slicers allow filtering by region, time, and category.
- **Drill Down**: Many visuals support drilling into specific products, states, or months.
- **Tooltips**: Hover on any chart element to see detailed metrics and comparisons.
- **Bookmark Views**: Save filtered views for recurring business reviews.

---

## 📐 Key Metrics Definitions

| Metric | Formula / Description |
|--------|------------------------|
| **Total Revenue** | Sum of order prices from `Orders_Africa` |
| **Delayed Orders %** | (Delayed Orders ÷ Total Orders) × 100 |
| **Average Product Rating** | Avg. of product `Rating` from `Products` |
| **Revenue by State** | Aggregated revenue by `Customer_Africa.State` |
| **On-Time Delivery Rate** | (On-time Orders ÷ Shipped Orders) × 100 |

---

## 📅 Seasonal Context in Africa

The seasonal sales patterns page considers regional events:
- **Holidays** (e.g., Eid, Christmas)
- **Back-to-School periods**
- **Black Friday & Cyber Monday**
- **Rainy/Dry Season impacts on logistics**

---

## 💻 App Access Instructions

1. Go to **Power BI Service** → Apps → *ShopNest Africa Analytics*
2. Click **Install** (if not already added to your workspace)
3. Use navigation pane or report tabs to explore data
4. Pin your favorite KPIs to a **personal dashboard**

---

## 🔧 Maintenance & Updates

| Task | Owner | Frequency |
|------|-------|-----------|
| Data Refresh Validation | BI Ops – Africa | Daily |
| Visual/Measure Updates | Regional Analytics Team | Bi-weekly |
| Regional Customizations | Power BI Lead | As needed |



---

_Last updated: June 22, 2025_
