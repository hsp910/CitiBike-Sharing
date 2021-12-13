# Citi Bike Sharing Challenge

## [View Full Workbook on Tableau](https://public.tableau.com/app/profile/harsh.patel6786/viz/CitibikeChallenge_16393434068320/CitibikeAnalysis)

## Overview
The purpose of this analysis is to help others decide if it is worth investing into bike sharing businesses like CitiBike has in other major cities. To help with this process we are using the data Citi Bike posts online to decide the viability and profitability of a bike sharing program, and we are using the same data to help determine the target audience from various factors, primarily gender and age. The data we are specifically looking at is Citi Bike's provided data for August of 2019 within New York City. From this data we are to clean it and use visualizations help illustrate as many trends and opportunities as possible for other cities.

## Resources

This Tableau analysis was created using the data provided by Citibike [following this link](https://s3.amazonaws.com/tripdata/index.html)

Make sure to download the csv for August of 2019 (201908-citibike-tripdata.csv to be exact).

## Results

The results shown will be mostly from the story created in the workbook linked above. It focuses on New York City as that is where the data is collected, but could be applied more widely if given extra attention to adjusting trends for those specific cities.

![August Peak Hours](https://i.imgur.com/usp3N4r.png)

During August the most popular hours in which people used these bikes were between 5 and 6 PM. There was also a smaller spike earlier in the morning at 8 AM. This points to a possibility that many of the people using this bike sharing program are actually using it as a part of their daily commute to and from work. However, this data is far from proving such an assumption and we must push forward with the results. 
![Trip Duration Overall](https://i.imgur.com/PPyKUVm.png)

This chart was created to show the trip duration for the majority of users. As we can see in the chart the majority of users are only riding these bikes for anywhere from 5-10 minutes before they reach their destination, and then almost none of the users are riding the bikes after 45 minutes. This means that most users are using the bikes to travel relatively short distances compared to those that might use ride sharing programs. 
![Trips by Weekday Heatmap](https://i.imgur.com/yRjXYbn.png)

This heatmap also helps prove the previous point about the bike sharing program being used most for daily commutes at 8 AM and 5 to 6 PM. This is even made more obvious by the fact that the heatmap shows much more usage at those times on weekdays compared to weekends. In fact weekend popularity is fairly consistent throughout the afternoon after 11 AM. For some odd reason Wednesdays are the least popular weekday while Thursdays are the most popular for the bike sharing program. Further research will be needed to answer a reason to why this is the case.

![User Trips](https://i.imgur.com/qfrBzpZ.png)

Now within this dashboard we have a multitude of different graphs to look at. First I would like to point out that the large majority of the userbase are subscribers to Citi Bike. This means that the most profits for Citi Bike comes from retaining users for the long term, meaning the best option is to incentivize customers to subscribe to the program through various means. Then you can see a breakdown of the total population of users by gender in the bottom left; this shows that the majority of users are male with nearly a quarter of them being female, and a portion of them not having a gender labeled. The gender breakdown shows that it may be possible to expand the female userbase of this program as very few women are using Citi Bike. The other possibility is to focus on men as a more likely source of long-term users.

![Trips by Weekday filtered by gender heatmap](https://i.imgur.com/SQN113D.png)

This heatmap primarily shows the same things shown in previous visualizations with the peak hours being the same for both men and women. This means that most likely men and women use the bikes for the same purpose and there for we can reliably expect demand the stay high at the same times from both parties.
![Start and Endpoint Geographic Heatmaps](https://i.imgur.com/78wSaPn.png)

Finally we have a map of New York City with the start and end points of each bike station spread across the city. Even though this is a city specifically of New York we can draw similar conclusions about the usage of bikes from things we can observe in this map. For instance, most of the largest circles on this map are in large population centers with the outskirts of New York City being much less popular for renting bikes. While there is still some popularity for the bikes in other areas, such as next to the waterfronts, we can reliably focus most of the bikes in the program on population centers and keep less for less popular centers for this reason.
## Summary

To further push this bike sharing business analysis we created an additional visualization on top of the expected parameters. The userdata provided by Citi Bike includes a birth year. This allowed us to create a small calculated field that roughly estimated the age of each person renting a bike from the bike sharing service by using a simple formula (2019 - Birth_Year). From this we compared the amount of rides people of certain ages went for and created this simple visualization:
![Trips made by age and gender](https://i.imgur.com/aXFY4IW.png)

As can be seen from the chart there is a single major outlier in the data. An unknown 52 year old seems to have done nearly 210000 rides which in most cases would be thrown out of any reasonable data set, but further research needs to be done to ascertain that is the best course of action. 

Another point to be made about future analysis would be a survey of Citi Bike's userbase to see the primary reasons they use the bike sharing program for. Reasons such as daily commutes, leizure, tourism, or just a one off to try the product. This data would be a lot more relevant to how to directly meet customer needs based on putting higher amounts of bikes and services in centers that would be used for purposes such as daily commutes. We could then compare it to our current data on gender, age, and any other metrics added in the future analysis to gain a broader understanding of the userbase of the product.  
