# Ride-Analysis-Dashboard
 Ride Booking Analytics – July Monthly Performance Review
🧩 Business Problem:
The ride-sharing platform is experiencing a high cancellation rate (~38%) despite generating 57M in revenue. The business seeks to understand:

Why are cancellations so high?

Which vehicle types, days, and locations perform best?

What actions can be taken to improve booking success and customer satisfaction?

 Tools Used:
Power BI: For interactive data visualization

SQL: For querying booking, vehicle, and customer datasets

Excel (optional): For pre-processing and validation

Dashboard Analysis:
Key KPIs:
Total Bookings: 103K

Completed Rides: 64K

Cancelled Rides: 39K

Cancellation Rate: 37.91% (critical issue)

Total Revenue: 57M

Avg. Booking Value: ₹548.75

Avg. Ride Distance: 14.19 km

 Deep Dive Analysis:
1. Daily Booking Trend
Bookings remained consistent (~3K daily).

Cancellation patterns are stable but persistent each day.

Peak revenue days are around July 1st and July 29th (~1.9M).

 2. Vehicle Type Performance
All vehicle types are equally utilized (≈14K bookings each), suggesting balanced demand.

Prime Sedan has the highest avg. booking value (₹557.81) and ride distance (15.76 km).

Mini has the lowest avg. ride distance (6.24 km), but similar booking value, suggesting inefficiency.

 3. Location-Wise Booking
Top pickup zones: Banashankari, Yeshwanthpur, RT Nagar.

These top 10 locations alone account for nearly 20% of bookings.

 4. Cancellation Insights
Highest cancellations by Driver: 18.4K (~47%)

Driver Not Found: 10.1K (~25.9%) → Opportunity for fleet/logistics optimization.

Cancellations by Customers: 10.4K (~27%) → Could indicate poor driver behavior, wait time, or pricing.

 5. Booking Value by Status
Success bookings contribute overwhelmingly to total revenue (~36M+).

Cancelled bookings contribute little or zero revenue, adding to opportunity cost.

 Business Insights:
Driver-side issues (no-shows or cancellations) are more frequent than customer-side, suggesting operational inefficiencies.

Revenue opportunity lost from 39K cancellations is significant (~37% potential increase in revenue).

Prime Sedan offers the highest revenue per km; worth expanding fleet in high-demand zones.

Locations like Indiranagar and Banashankari show consistently high booking counts → Target for customer loyalty or surge pricing.

 Recommendations:
Reduce Cancellations:

Implement driver penalty system for frequent cancellations.

Use machine learning to predict “high cancellation risk” rides (based on time, location, vehicle).

Improve driver availability in peak hours/locations.

Fleet Optimization:

Increase Prime Sedan and eBike vehicles in high-demand areas to maximize revenue per km.

Reduce Mini fleet or assign to short-distance locations to avoid underutilization.

Customer Experience:

Offer incentives or coupons for repeat users in high-cancel zones.

Introduce real-time driver tracking and cancellation feedback.

Operational Improvement:

Set driver allocation KPIs: Driver response time, success ratio, cancellation score.

Optimize shift scheduling for drivers in high booking areas.
