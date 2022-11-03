# Ford GoBike Data Visualization
## by Mofeoluwa Jide-Jegede


## Ford GoBike Trip Data

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the month of February 2019. It was provided by the Udacity platform.

>The dataset features information about **183412** rides with **16** variables. The columns which represent the variables include:
1. Duration of trip(in seconds)
2. Start time, 
3. End time, 
4. Start_station_id
5. Start_station_name
6. Start_station_latitude
7. Start_station_longitude
8. End_station_id
9. End_station_name
10. End_station_latitude
11. End_station_longitude
12. Bike_id 
13. User_type
14. Member_birth_year
15. Member_gender
16. Bike_share_for_all_trip.


## Data Exploration

>I investigated distributions of individual variables, checking for unusual points and outliers. I take a deeper look to clean things up and prepare to look at relationships between variables.

> he analysis focused on understanding the best times to display advertisements to target specific people. What kind of reach do advertisements have on ford go bike users based on the patterns in the data?


>Some of the questions that would help understand this include:
1. What is the gender distribution across bike stations?
2. What are the busiest weekdays?
3. What is the busiest time of day for riders of different genders?
4. Age distribution of riders
5. Busiest stations at each time of the day
6. Most used bikes?

I dropped the columns I didn't need for the purpose of this analysis.

I decided to create a duration in minutes column because I felt it was a more quantifiable measure of time than duration in seconds.

The start and end time had to be broken into subsets of Months, Weekdays, and Hours.

I created an Age column calculated from the member_birth_year column. Ages above 80(to the max of about 140) were also dropped as there is a likelihood of ages older than that being an error. Even if it wasn't an error, for this analysis, it is not needed.

I tidied the data by dropping the "Others" entries as it is unnecessary for this analysis.


## Summary of Findings

> Here are some findings that I made in the course of this exploration:
1. Male riders are 70% of the total riders.
2. Suscribers make 90.59% of the total riders.
3. The weekends have the least activity of riders.
4. Thursday is the busiest day of the week.
5. Most riders are in their 20s & 30s.
6. Most rides have a duration of less than 200minutes.
7. Women almost never go riding late at night.
8. Market St at 10th St is the busiest station.


## Key Insights for Presentation

> 
1. The Subscribers are 90.53% of total riders. This is a reasonable percentage for Ford GoBike as a business. However, if they were looking to convert more customers to subscribers, they could take an approach to incentivize long trips. As seen from the scatter plots, some customers take long trips. If there was an incentive for cheaper rates for longer trips as subscribers, FordGobike could get their subscriber count up.

2. The best location and time for the most reach of female riders is Berry St at 4th St on Thursday mornings.

3. The best location and time for the most reach of female riders is Market St at 10th St on Thursday mornings.

4. The best time to target older riders with ads is early mornings on Thursdays.
