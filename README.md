# Download Data in https://www.rakamin.com/mini-project/investigate-hotel-business-using-data-visualization/63 
# Handle Missing Value
- Children is handled by mode values
- Agent is handled by median values
- Company is handled by median values
- City is handled  by mode values
# Feature Extraction
- Visitor = adult + children + baby
- Total_Booking = previous_cancellations + previous_bookings_not_canceled
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
