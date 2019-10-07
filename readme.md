# Ford GoBike Data Analysis
## by Janani R


## Dataset

Each trip is anonymized and includes:

1. Trip Duration (seconds)<br>
2. Start Time and Date<br>
3. End Time and Date<br>
4. Start Station ID<br>
5. Start Station Name<br>
6. Start Station Latitude<br>
7. Start Station Longitude<br>
8. End Station ID<br>
9. End Station Name<br>
10. End Station Latitude<br>
11. End Station Longitude<br>
12. Bike ID<br>
13. User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)<br>
14. Member Year of Birth<br>
15. Member Gender

There were 519700 records in which high amount of variation existed with respect to duration with a standard deviation of 3444. But 75% of the values lied below 1000 which was considered while trimming outliers. 


## Summary of Findings

1. Trip Duration statistics revealed that 75% of the values were below 1000, so outliers were removed using Z-Score as reference. 
2. Going further with the trimmed dataset, I noticed that Customers on average spent more time riding than subscribers.
3. Age range of most riders was found to be 30-40.
4. One of the most interesting observations was the relationship between user type and start hour of the trip. While Subscribers rented it in the mornings and evenings, Customers rented it sporadically, peaking slightly in the afternoon, suggesting that Subscribers used the bikes as a mode of transport for work.
5. It was also found that there was an interesting relationship between the time taken to complete a trip and the starting hour. Presumed to be an indication of traffic, further investigation was done taking the most trafficked endpoints as reference. This only proved the presumption.

## Key Insights for Presentation

Focusing on trip duration, and the interaction of other variables with it, it was noticed that on average
1. Trips lasted around 14 minutes.
2. Subscribers rode faster than customers.
3. Trips took more time during the 9 AM to 6 PM timeline, irrespective of start and end points.