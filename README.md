# Hotel Bookings Power BI Dashboard

A 3-page interactive Power BI dashboard built on 
119,000+ real hotel bookings from 2015–2017.

## Pages

**Overview** — Total bookings, revenue, cancellation 
rate, bookings by hotel type and month

**Revenue Analysis** — Monthly revenue trends, top 10 
countries, market segment breakdown, avg daily rate

**Booking Behaviour** — Lead time distribution, 
length of stay, repeat guests, cancellations by segment

## Key Findings

- Total revenue: 42.7M across 117K bookings
- 37% cancellation rate — Online TA highest risk segment
- Portugal is the top revenue market
- Resort Hotel guests stay longer, City Hotel books later
- 97% of guests are first-time visitors

## Tools Used

- Power BI Desktop
- Power Query (M language) for data cleaning
- DAX for calculated measures
- Dataset: Hotel Booking Demand 
  (Kaggle — Jesse Mostipak)

## Data Cleaning Steps

1. Removed zero-rate bookings (ADR = 0)
2. Removed company and agent columns
3. Replaced null country values with Unknown
4. Created arrival_date from 3 separate columns
5. Created total_nights (weekend + weekday stays)
6. Created total_revenue (ADR x total_nights)
