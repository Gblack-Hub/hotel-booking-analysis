# hotel-booking-analysis

## Project Objective
The objective of the project was to help the hotel management improve its revenue generation and overall booking operations by analyzing historical reservation data. Based on the analysis, a dashboard was created to provide valuable insights to executives regarding the hotel's performance, including seasonal trends and cancellation patterns across the different market segments and booking channels. The dashboard was intended to help the hotel's management to make better decisions to improve its revenue and bookings.

## Dashboard
Appropriate chart types (Line graph, Column chart, Bar chart and pie chart) were used to represent the metrics and insights. Interactive features such as filters, dropdowns, and tooltips were used to provide detailed information.

<img width="2835" height="1587" alt="hotel-booking-dashboard" src="https://github.com/user-attachments/assets/ed24fb7e-5d01-4455-91b6-149995ff6f7f" />

## Data modelling and Relationships
The data was designed using the Star Schema, where the different dimension tables were connected to the fact table in a one-to-many relationship.

### Dimension tables created:
- hotel_dim
- location_dim
- date_dim
- market_segment
- meal_cost
<img width="2457" height="1521" alt="hotel-booking-relationship" src="https://github.com/user-attachments/assets/cd0ea516-6f57-42c5-82f6-f8625b95ae61" />

## Business Questions and Metrics
- How does seasonality affect booking volumes month-over-month?
- Which geographic regions or countries contribute the highest number of guests?
- Which market segments and booking channels are the most effective at driving reservations?
- What are the total booking volume, total revenue, and average daily rate (ADR) for the 2018–2020 period?


### KPIs that help answer the business questions:
- Total Bookings (across both hotels)
- Total Revenue
- Total Booking Cancellations
- Average Daily Rate

## Insights
- The properties brought in a total of $39M in revenue from 101K bookings, with an Average Daily Rate (ADR) of $104.

- Bookings tend to follow a distinct seasonal curve, with the peak during the summer months of July and August and the lowest bookings during the winter months of December and January.

- Portugal is the dominant market for bookings with 34K bookings, which is nearly triple the bookings for the United Kingdom market (12K).

- Online Travel Agents (Online TA) generate the most bookings for the company with 57K bookings. Direct bookings rank third, with 14K bookings.

- A significant portion of revenue is lost to cancellations, with 26.57% (27K) of bookings being cancelled.

## Recommendation
- **Adjust pricing based on the season:**

  Aim to increase revenue during the peak months of July and August with dynamic pricing and length-of-stay restrictions, and offer promotions during the off-season of December/January to increase bookings.

- **Capitalize on regional strengths:**

  Continue to market aggressively in Portugal to maintain the current customer base, and analyze the acquisition strategy in Portugal to replicate it in other countries of interest such as the UK, France, and Spain.

- **Incentivize direct bookings:**

  Since the majority of bookings are from OTAs, the commission fees must be high. To reduce this, offer perks, loyalty points, or slight discounts to guests who book directly.

- **Mitigate the high cancellation rate:**

  A cancellation rate of over 26% should be reduced. Possible solutions include offering discounts on non-refundable bookings, requiring a deposit at booking for peak-season reservations, and tightening the cancellation policy.
