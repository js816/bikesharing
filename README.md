# Overview of the project 

[Link to Tableau Story](https://public.tableau.com/app/profile/josh.stephens6499/viz/BootCamp-NYCCitiBikeChallengeVisualizations/NYCCitiBike) 


## Purpose

The purpose of this project was to develop visualizations of the NYC Citi Bike sharing program.  The dataset contains bicycle ride data from August 2019.  Analyzing this data can be helpful in understanding the potential success of a similar hypothetical program in Des Moines, IA.  


## Background

According to the current information on the NYC Citi Bike program [website](https://account.citibikenyc.com/access-plans), there are a number of ways to utilize the program.  For $179 annually, members can take unlimited rides up to 45 minutes.  Customers who are not members such as tourists, can pay $3.50 for a ride up to 30 minutes (or $15/day).  Alternatively, ebikes which are powered, are $0.12/minute for members and $0.18/minute for non-members.  The [program](https://www.citibikenyc.com/how-it-works) boasts 20,000 bikes and over 1,300 locations.  (The dataset analyzed contained data for about 14,000 bikes and about 800 locations.)

The program has a 3.5 (out of 5) rating on [Tripadvisor](https://www.tripadvisor.com/Attraction_Review-g60763-d7071917-Reviews-Citi_Bike-New_York_City_New_York.html).  The reviews highlight some positive aspects about the program.  There are also some complaints such as charging $4 per 15 minutes after the first 30 minutes.


# Visualizations


## Checkout Times for Users

![Chekout_times_for_users](https://user-images.githubusercontent.com/82730954/127708587-fc35f4da-820e-4601-a7cb-46c1294a2252.PNG)

The graph above shows the number of rides based on duration.  The y-axis shows the number of rides at each duration by minute across the x-axis.  While the graph can be filtered to show other durations, it is currently displaying rides up 2 hours 59 minutes.  The left pane shows rides less than an hour, the center pane shows rides 1 hour to 1:59, and the right pane shows rides 2 hours to 2:59.

The graph shows that the vast majority of rides are of a short duration.  Beyond about 30 minutes, the number of rides during the entire month dropped quickly and remained at a very low level which is understandable given the additional charge beyond 30 minutes for customers.  

## Checkout Times by Gender

![Checkout_times_by_gender](https://user-images.githubusercontent.com/82730954/127708828-b3746425-072a-4263-bc42-8d04d5ecad15.PNG)

The graph above shows the same checkout time by gender.  The same pattern holds true across gender.  This graph also demonstrates that the majority of rides are taken by males.

## Trips by Weekday per Hour

![Trips_by_weekday_per_hour](https://user-images.githubusercontent.com/82730954/127708859-d087f9be-0e1d-44de-9d1c-df5652c0664e.PNG)

The above graph shows ride start times by hour (on the y-axis) and weekday (on the x-axis).  The data show that during the week, peak times are before and after normal working hours, although that does shift some on Thursdays and Fridays.  Weekend rides start to increase later in the day and are more consistent throughout the day.  Nighttime and early morning hours are the least popular times.

Understanding peak and off-peak times is important in understanding when bikes can be serviced and redistributed as needed without impacting the supply available.

## Trips by Gender (Weekday per Hour)

![Trips_by_gender_weekday_per_hour](https://user-images.githubusercontent.com/82730954/127708878-855317d1-f405-4fca-b59c-81b6aae2fdb4.PNG)

The above chart shows the same data, trips that start during each hour of the day for each day of the week, and breaks out the data by gender.  The chart, which can be filtered by gender, shows that similar usage patterns hold true for each gender.


## User Trips by Gender by Weekday

![User_trips_by_gender_by_weekday](https://user-images.githubusercontent.com/82730954/127709139-74f6fab9-e134-436c-b4ce-6b0d76de2925.PNG)

The above visualization shows that the majority of rides are taken by members who are male.  This pattern holds true across all days of the week.

Understanding this can help cater the marketing message for the program in Des Moines.  It may also demonstrate that there is a potential to increase female utilization of the program.

## Rides by Usertype

![Rides_by_usertype](https://user-images.githubusercontent.com/82730954/127708914-5de96e72-c310-48ad-9c85-b0201680ca37.PNG)

The pie chart shows that more than 4 out of every 5 rides was taken by a subscriber in the NYC program.  Understanding this seems to show that optimizing the subscription program could be key to the program’s success in Des Moines. 

A variety of subscription models should be considered to gain momentum and help prove the concept.

## Top Staring Locations

![Top_starting_locations](https://user-images.githubusercontent.com/82730954/127708933-aba1d4ea-4a78-429a-a19e-1f51532ff4f1.PNG)

There are a large number of stations across the New York area where bike rides can begin and end.  The map above plots starting stations.  The larger and darker the marker, the more rides started at that station.  

Making the program convenient and useful to potential customers and subscribers would be an important part of helping set the program up for success.


# Summary

It was a pleasure to be involved in visualizing the NYC Citi Bike program data.  The data analyzed show that the program generated a large number of rides throughout the month and seemed popular throughout various portions of the city.  

## By Individual Riders

Additional insight could be gained if the data had a unique, anonymous ID for each rider.  Understanding additional factors could provide a greater depth of knowledge.  These could include:  the average number of rides taken by each subscriber/customer and how often a rider switches bikes to avoid the charge after 30 minutes for customers and 45 minutes for subscribers.

## Additional Visualizations

Additional visualization could be performed on weekends and middays.  Looking at these patterns could potentially allow discounted rates or subscriptions to help increase utilization in slower periods.

Also, looking specifically at more suburban stations might provide greater insight into how the program could transfer to Des Moines.  Much of NYC is densely populated and congested thus potentially making bikes preferable to cars.  Looking specifically at more suburban areas might help demonstrate the programs potential or could identify potential difficulties in Des Moines.

## Suggestions for additional analysis

While there were a number of insights gained from analyzing the data from New York, it could also be helpful to examine data from cities closer in population and geographic location to Des Moines.  It is possible that various factors, such as consumer demand, geographic layout, and city density, could impact the potential success of the program.

In addition to analyzing ride data, financial data should also be examined to help ensure the long-term success of the program.

## Data Reliability

Also, while birthyear is provided in the dataset, there are a number of outliers.  For example, riders who reported birthyears from 1887-1918, who would have been 100-132 years old in 2019, accounted for nearly 1,000 rides.  If birthyear is used in any analysis, it is suggested that a cutoff be determined and years beyond that be excluded as they seem to be unreliable.
