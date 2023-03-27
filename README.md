# Download Data in https://www.rakamin.com/mini-project/investigate-hotel-business-using-data-visualization/63 
# Handle Missing Value
- Children is handled by mode values
- Agent is handled by median values
- Company is handled by median values
- City is handled  by mode values
# Feature Extraction
- Visitor = adult + children + baby
- Total_Booking = previous_cancellations + previous_bookings_not_canceled + booking_changes
- Total Stay = Stays in Weekend Nights + Stays in Weekdays Nights
- Segmentation = categorization of lead time (short, middle, long, too long")
# Invalid Values
- required_car_parking_spaces = "Reqired" and "Not Required"
- meal = "Breakfast", "Dinner", "Full Board", and "No Meal"
# Split data
- test size = 0.2 , y_test = "is_canceled" , random_state = 42
# Handle Outliers
- Stays in Weekend Nights > 11
- Stays in Weekdays Nights > 35
- Days in Waiting List > 300
- ADR > 1000
- Visitor > 15
- Total_Booking > 40
- 170 < Company < 190
- Agent IQR
# Business Insight
- In 2018 there was a surge in visitors coming to book hotels.
- However, as time goes by, promotions that are not updated make potential visitors or customers experience a decrease in their level of interest in 2019.
- Another thing is that Covid-19, which has attacked other countries, has made many parties prefer to be vigilant rather than booking a hotel.
- The most bookings for hotel rooms in 2018 were in December. This is very reasonable because there are big days like Christmas and New Years.
- From 2017 to 2019, the visitors who booked the hotel mostly booked in the middle of the year. This happens because there are school holidays, Eid holidays, and several other jobs.
- The duration of stay can affect the cancel rate if the facilities are not good, the service and behavior of hotel residents, both officers and neighbors, are not good.
- Information was obtained that prospective visitors who waited a long time (more than 365 days) tended to cancel.

