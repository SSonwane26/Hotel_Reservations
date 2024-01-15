# Hotel_Reservations
Power BI [Report](https://app.powerbi.com/view?r=eyJrIjoiZGJiOGNlYmQtNTVjNy00ZDQ1LWEyNDctZDBhZGMwNjQ0MzUwIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&pageName=ReportSection6c930272fe1281412343)

Perform EDA using Power Query and Data Visualization using Charts and Graphs using Power BI.

The online hotel reservation channels have dramatically changed booking possibilities and customers’ behaviour. A significant number of hotel reservations are called-off due to cancellations or no-shows. The typical reasons for cancellations include change of plans, scheduling conflicts, etc. This is often made easier by the option to do so free of charge or preferably at a low cost which is beneficial to hotel guests but it is a less desirable and possibly revenue-diminishing factor for hotels to deal with.

Steps for Data Analysis
- Defining the problem: There is more monthly booking cancelations. So, task is to reduce monthly cancelations. 
- Data collection: Data is collected from hotel servers and from entry sheets.
- Data cleaning and pre-processing: Power Query for data cleaning.
-	Exploratory data analysis: QnA type data analysis.
-	Applying analytical techniques: Use DAX Functions for total nights, total bookings etc. 
- Data Visualization: Used charts and graphs for data visualizations.
- Interpretation and reporting: Create clean and beautiful Dashboard. 

## About Project
**Context**

The online hotel reservation channels have dramatically changed booking possibilities and customers’ behaviour. A significant number of hotel reservations are called-off due to cancellations or no-shows. The typical reasons for cancellations include change of plans, scheduling conflicts, etc. This is often made easier by the option to do so free of charge or preferably at a low cost which is beneficial to hotel guests but it is a less desirable and possibly revenue-diminishing factor for hotels to deal with.

**About this file**

The file contains the different attributes of customers' reservation details. The detailed data dictionary is given below.

**Data Dictionary**

- Booking_ID: unique identifier of each booking
-	no_of_adults: Number of adults
-	no_of_children: Number of Children
-	no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
-	no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
-	type_of_meal_plan: Type of meal plan booked by the customer:
-	required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
-	room_type_reserved: Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels.
-	lead_time: Number of days between the date of booking and the arrival date
-	arrival_year: Year of arrival date
-	arrival_month: Month of arrival date
-	arrival_date: Date of the month
-	market_segment_type: Market segment designation.
-	repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
-	no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
-	no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking
-	avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (In euros)
-	no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
-	booking_status: Flag indicating if the booking was cancelled or not.

 
**Steps for Data Analysis**

-	Defining the problem: There is more monthly booking cancelations. So, task is to reduce monthly cancelations. 
-	Data collection: Data is collected from hotel servers and from entry sheets.
-	Data cleaning and pre-processing: Power Query for data cleaning.
-	Exploratory data analysis: QnA type data analysis.
-	Applying analytical techniques: Use DAX Functions for total nights, total bookings etc. 
-	Data Visualization: Used charts and graphs for data visualizations.
-	Interpretation and reporting: Create clean and beautiful Dashboard. 

Certainly! Here are some questions that can explore using the provided dataset in Power BI:

1. What is the distribution of bookings by market segment type?
2. How does the average price per room vary across different room types?
3. What is the trend of bookings over time (by month or year)?
4. What is the average lead time for bookings?
5. How does the number of special requests correlate with the booking status?
6. What is the distribution of booking statuses (cancelled vs. not cancelled)?
7. Is there a correlation between the number of previous cancellations and the booking status?
8. How does the average price per room change based on the type of meal plan selected?
9. What is the proportion of repeated guests among all bookings?
10. Is there a relationship between the number of adults/children and the room type reserved?

**Insights we get**

1.	From all non-cancelled bookings, across all room types and meals, the average prices are 103.4 euros.
2.	The prices in the hotel are much higher during the month of summer season and winter season respectively.
3.	Repeated guests do not cancel their reservations. Of course, there are some exceptions. Also, most of the customers are not repeated guests.
4.	Most people do not seem to prefer to stay at the hotel for more than 1 week. But it seems normal to stay in hotel for up to 12–15 days. Although this changes according to the segments, staying longer than 15 days certainly creates outliers for each segment.
5.	Customers from Aviation Segment do not seem to be staying at the hotel and have a relatively lower day average.
6.	The weekends and weekdays averages are roughly equal.
7.	Customers in the Aviation Segment are likely to arrive shortly due to business. 
8.	The cancellation rate for groups is equal to 50%.
9.	The cancellation rate for offline and online is greater than 50%. Direct segments have a lower rate of cancellation.
10.	When the lead time exceeds about 60, guests frequently cancel their bookings (cancellation rate is higher after this point). Additionally, people want their vacation or work schedules to be calculated across 100 days, or 50% of the data.
11.	The Hotel sees an increase in visitors in the spring and fall when rates are also the greatest. Less people arrive in February and March, when the prices are still lower.

**Conclusion:**

For reduction of cancellations, we have to reduce lead time approx. 33%. When lead time is below limit hotel gives bonus points to customers for their future reservations. We have to introduces attractive schemes like next booking vouchers, combos (meal type + room type) etc.
