# Bikesharing


## Overview of the Analysis
### Purpose
The purpose of this analysis is to use tableau to analyze data and create visualizations to present a business proposal for a bike sharing company. Citibike is a bike sharing business installed in New York City. The idea is to take this concept and try to start a similar business in Des Moines, Iowa. After finding a potential investor, the task is now to use the August data available from Citibike to see how it works in New York, and then how it could work in Des Moines. 


## Results
![viz_1](https://github.com/DaniliukK95/bikesharing/blob/main/images/viz_1.png)

The visualizations in the introductory panel show four key aspects:
- The total amount of trips for the month of August (2,344,224). 
- The type of customers that use the bikes (short term customers: 443,865, and annual subscribers: 1,900,359).
- The gender of the trips for August (male, female, and unknown). Male customers made up more than half of the trips with a total of 1,530,272. Then there were 588,431 female customers, and 225,521 unknown customers. 
- The number of trips that occurred at different hours of the day. This will show the most popular times that people take trips. We see increases in usage from 7AM to 9AM and then from 4PM to 7PM. 

![viz_2](https://github.com/DaniliukK95/bikesharing/blob/main/images/viz_2.png)

These two visualizations show the checkout times for users. This will tell us how long people are using the bikes for in trips.
- The top visualization shows the checkout times for all users regardless of subscription type and gender. We can see that most trips span five minutes of usage. Majority of the trips recorded last less than an hour. 
- The bottom visualization shows the checkout times based on gender. We continue to see the same trend with the most trips lasting less than an hour. 


![viz_3](https://github.com/DaniliukK95/bikesharing/blob/main/images/viz_3.png)

The two visualizations here are heatmaps showing the trips based on time of the day, and day of the week. 
- The left visualization shows all user types and genders. From this heatmap we can see that the 7AM-9AM and 4PM-7PM usage are mainly during the weekdays. We also can see that there is steady usage from 10AM-6PM on the weekends. 
- The right visualization shows the same data but now by gender. We continue to see the same trend as the left visualization.

![viz_4](https://github.com/DaniliukK95/bikesharing/blob/main/images/viz_4.png)
The last visualization is another heatmap this time by gender and customer type. We see here a huge connection with the type of user and the days the bikes are used. It seems that short term customers mainly use the bike services on the weekend while annual subscribers are mainly using the bikes on weekdays during the commuting hours. We also see that there is very little data for unknown genders as annual subscribers, but more data for unknown genders as short-term customers. 


## Summary
The results show that Des Moines can expect annual subscribers as their main source of customers. Depending on the gender ratio in Des Moines, it seems that there will be more male than female customers. Because most of the rides appear to be coming during commuting hours, it would be expected to see traffic heavily during 6AM-9AM and then from 5PM-8PM which is when people are usually going to work and leaving work. There will also be traffic during the weekends from about 10AM-6PM which will most likely come from the short-term customers. Finally, from my observations, it does not seem that gender makes a huge difference, but this could be skewed because of the ratio of men to women. 

To obtain more data that could help with understanding how this business works and if it can be profitable is Des Moines, I would create two extra visualizations: 
- The first visualization would be to grab the data from all the months of the year and see the total number of trips for each month. Because of the way Citibike is set up with fixed stations, we would need to see how this business does year-round and see if it will be profitable or not. Depending on Des Moines weather year-round, there might be periods where the bikes shouldn’t be available to avoid damages or wasted resources. 
- The second visualization I would create would also use the year-round data but this time focusing on the user type along with the time of day and day of the week. This will help to show when there is a rising or falling of short-term customers which could be mainly tourists. During these months, there can be extra effort to increase or decrease the number of bikes available. This can also give us insights on annual subscriber usage. 


## Link to Tableau Story
[Kevins CitiBike Tableau Story](https://public.tableau.com/app/profile/kevin.daniliuk/viz/CitibikeAnalysis_16679485688230/CitiBikeChallengeStory)
