# Hotel Booking Analysis

## Introduction
This project analyzes the hotel's historical booking data to identify insights into the hotel’s performance. In order to optimize revenue generation and streamline booking operations, the hotel management required a deeper understanding of their historical reservation data.

The project includes an analysis of the seasonal booking patterns and cancellation rates of the hotel's different market segments and booking channels. These analyses will be presented in an executive dashboard to give the hotel management team a better understanding of the hotel's performance and to enable them to make informed decisions that will lead to sustainable growth of the hotel.

## Problem Statement
The hotel management lacked centralized visibility into key booking metrics, which made it impossible for them to maximize their profitability. Specifically, they needed to address their high cancellation rate (over 26%), their high commission costs due to their reliance on OTAs, and their severe seasonal demand fluctuations. Without an understanding of their booking and geographic trends, they could not optimize their pricing or marketing to increase their profitable direct bookings.

## Data sourcing
Data is sourced from a spreadsheet.
[Google Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vS52d97uM74ii6cWBw03FvzxRB8LP54dAe-PNkCoRR84SglMJRw6fhpjhM-PjauJA/pubhtml)

## Data transformation and cleaning
The data transformation and cleaning process is documented [in this file](https://github.com/Gblack-Hub/hotel-booking-analysis/blob/14054bffca6b299c2610be73023e05d2003e91ad/Data_Transformation_and_Cleaning.pdf).

## Data modelling
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

## Data analysis and Visualisation
### Insights
- The properties brought in a total of $39M in revenue from 101K bookings, with an Average Daily Rate (ADR) of $104.

- Bookings tend to follow a distinct seasonal curve, with the peak during the summer months of July and August and the lowest bookings during the winter months of December and January.

- Portugal is the dominant market for bookings with 34K bookings, which is nearly triple the bookings for the United Kingdom market (12K).

- Online Travel Agents (Online TA) generate the most bookings for the company with 57K bookings. Direct bookings rank third, with 14K bookings.

- A significant portion of revenue is lost to cancellations, with 26.57% (27K) of bookings being cancelled.

### Visualization
<img width="2835" height="1587" alt="hotel-booking-dashboard" src="https://github.com/user-attachments/assets/ed24fb7e-5d01-4455-91b6-149995ff6f7f" />

## Recommendations
- **Adjust pricing based on the season:**

  Aim to increase revenue during the peak months of July and August with dynamic pricing and length-of-stay restrictions, and offer promotions during the off-season of December/January to increase bookings.

- **Capitalize on regional strengths:**

  Continue to market aggressively in Portugal to maintain the current customer base, and analyze the acquisition strategy in Portugal to replicate it in other countries of interest such as the UK, France, and Spain.

- **Incentivize direct bookings:**

  Since the majority of bookings are from OTAs, the commission fees must be high. To reduce this, offer perks, loyalty points, or slight discounts to guests who book directly.

- **Mitigate the high cancellation rate:**

  A cancellation rate of over 26% should be reduced. Possible solutions include offering discounts on non-refundable bookings, requiring a deposit at booking for peak-season reservations, and tightening the cancellation policy.
