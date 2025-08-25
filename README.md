# Hospitality_Revenue_Analysis

## Overview
This project was developed as part of the Codebasics Resume Challenge and centres on AtliQ Grands, a fictional chain of five-star hotels across India. The company has been experiencing a decline in market share and revenue in the luxury/business hotel segment, primarily due to inefficient management decisions. This project leverages business intelligence and data analytics to support strategic decision-making and business revitalization.

---
## Problem Statement
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate "Business and Data Intelligence" to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.
Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

---
## Objective 
To design a data-driven Power BI dashboard that helps AtliQ Grands identify revenue trends, optimize pricing strategies, and improve booking efficiency across properties by analyzing key hospitality metrics such as ADR, RevPAR, Occupancy %, and platform performance.

---
## Hotel & Data Overview
- Hotel Chain: AtliQ Grands
- Locations: 4 major cities across India
- Properties: 7 five-star hotels
- Room Categories: Standard, Elite, Premium, Presidential
- Booking Channels: 6 key online platforms plus other direct channels

---

## Data Sources Used
- dim_date: Calendar data including week numbers, months, and day types
- dim_hotels: Property IDs, names, categories, and locations
- dim_rooms: Room class information
- fact_aggregated_bookings: Daily bookings, capacity, check-in dates by room category and hotel
- fact_bookings: Detailed booking information (ID, guest count, revenue, platform, status, and ratings)

--- 
## KPIs Created Using DAX
- Total Bookings | Total Revenue | Total Capacity | Average Rating | Realisation %
- Total Successful Bookings | Occupancy % | Total Cancelled Bookings
- Cancellation Rate | Revenue Loss | ADR | RevPAR | No Show Rate % | DSRN 

--- 
## Tools & Technologies Used
- Power BI – for interactive data visualization and dashboard development
- DAX – for creating dynamic measures and KPIs
- Excel / CSV – for importing and cleaning sample hospitality data
- Data Modeling – building relationships and optimizing the data model

---
## Key Insights
- Mumbai leads in revenue generation, contributing 668.6M, followed by Bangalore (420.4M), Hyderabad (325.2M), and Delhi (294.5).
- Luxury rooms contributed the most to total revenue (61.61%), while the Business category contributed 38.39%.
- Weekends outperform weekdays in both RevPAR (₹7,927 vs ₹7,101) and occupancy (62.08% vs 56.0%) — suggesting pricing strategies can be optimized for weekends.
- AtliQ Exotica and AtliQ Palace are the top revenue-generating properties with over ₹300M each.
- AtliQ Bay (Mumbai) and AtliQ Seasons have the lowest guest ratings (2.3–2.4) and higher cancellation percentages.
- The “Others” booking platform has the highest share of bookings (40.91%) but also the most cancellations (~13.7K).
- Standard and Presidential rooms have the highest cancellation rates compared to other room types.
- Overall occupancy rate is 57.79% with an ADR of ₹12,695 and a RevPAR of ₹7,337.
- Guest satisfaction averages 3.62 out of 5 across all properties.

---
## Recommendations
- Enhance Customer Ratings:
Customer ratings can be enhanced by delivering exceptional service, maintaining high standards of cleanliness, and offering quality food, all of which directly impact bookings and overall revenue.

- Optimize Room Pricing Based on Occupancy:
With an overall occupancy rate of 57.9%, the management should explore dynamic pricing strategies, particularly for properties with lower occupancy, to boost room utilization and increase revenue.

- Implement Dynamic Pricing:
As the Average Daily Rate (ADR) is almost the same on weekdays and weekends, using dynamic pricing for all properties and platforms can help increase revenue.


---
## Acknowledgments
Special thanks to Codebasics for hosting this insightful challenge and providing a real-world case study for hands-on analytics learning
