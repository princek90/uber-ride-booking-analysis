# Uber Ride Booking Sales & Performance Analysis

Interactive Power BI dashboard analyzing ride-booking data — revenue, booking trends, and driver/customer ratings across vehicle categories.

*Built using a publicly available ride-booking dataset for practice/portfolio purposes.*

**Tools:** SQL · Python (Pandas) · Power BI

---

## Problem Statement

Ride-booking platforms generate large volumes of transactional data across bookings, revenue, distance, and ratings — but without proper analysis, it's hard to answer basic business questions like: Which vehicle categories drive the most revenue? Where are bookings being lost? How does performance vary month to month?

## Approach

1. **Data Cleaning & Structuring** — Used Python (Pandas) to clean and prepare the raw booking dataset, handling missing values and inconsistent formatting.
2. **Analysis** — Used SQL to aggregate and validate key metrics: completed bookings, lost bookings, revenue, and distance.
3. **Visualization** — Built an interactive Power BI dashboard to explore booking and revenue trends by month/quarter, vehicle category, and location.

## Key Metrics Tracked

- Completed Bookings: 93K
- Revenue: 51.85M
- Lost Bookings: 57K
- Total Distance: 3M
- Average Distance: 25
- Average Driver Rating: 4.23 / 5
- Average Customer Rating: 4.40 / 5

## Dashboard Preview

## Key Insights

- **Auto and Bike** are the top revenue-generating vehicle categories, followed by Go Mini and Go Sedan.
- Booking volume shows a clear **seasonal pattern**, peaking around Quarter 3.
- A notable share of bookings (57K) were **lost**, highlighting an area for further investigation — e.g., cancellations or driver availability.
- **Khandsa** and **Ashram** emerged as the top pickup and drop locations respectively, useful for driver allocation planning.
- Customer ratings (4.40) are consistently higher than driver ratings (4.23), which could be worth exploring further.

## Files in This Repo

```
├── scripts/            → Python data cleaning scripts
├── sql/                → SQL queries used for aggregation
├── dashboard/          → Power BI (.pbix) file
├── screenshots/        → Dashboard preview images
└── README.md
```
