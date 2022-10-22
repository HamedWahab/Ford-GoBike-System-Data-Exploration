# Ford GoBike System Data Exploration
## by Wahab Hamed Ayomide


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There are 183,412 rides (rows) made in the dataset with 16 details ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip') about the rides.


## Summary of Findings

- The time of the day with the most rides is Morning (00:00 - 11:59 hours) while Night (19:01 - 23:00) had the least number of rides.
- The day of the week with the most rides is Thursday while the least number of rides are taken during weekends (Saturday and Sunday). 
- Most of the people take rides during weekdays (Monday to Friday) compared to weekends.
- Most rides (about 89%) are taken by the subscribers and about 11% are taken by customers. 
- Majority of the rides are less than 40000 seconds in duration. 
- Rides are started mostly between 8am in the morning and 5pm in the evening. 
- Majority of the riders are male which is about 75% of the gender population.




## Key Insights for Presentation

- The number of rides taken in the morning is much more than ones taken in afternoon or evening during weekdays while on the weekends the number of rides in afternoon are more than ones taken during morning, evening or night.
- The day of the week that most trips are taken (Thursday) is not dependent on if the user is a subscriber or a customer. However, it was discovered that Subscribers mostly used bikes on weekdays (Monday - Friday), while customers bikes usage was about the same for the whole week with a significant increase on Saturday and Sunday (weekends).
- On average, subscriber users tend to ride the bikes in lesser duration than customer users.
- Saturdays and Sundays have the longest avaerage ride duration among the days of the week since the weekends are majorly used by the customers.
- Most rides for subscribers started at 8am and 5pm while customer rides were more flexible but most started at 5pm.

> Further analysis strengthened the earlier observations of the relationship between the user_type, the ride duration, days of the week and the starting hours in this exploration. It showed that on average, customers rides lasted longer than subscribers rides on every day of the week. Also, subscribers tend to have stable ride durations at the across the starting hours while the customers have relatively flexible ride durations.

