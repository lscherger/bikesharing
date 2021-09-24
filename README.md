# bikesharing
## Overview of the Analysis
In this analysis, Citibike data from New York City is analyzed and visualized using Tableau Public to show to an angel investor, who might want to help start a similar bike sharing company in Des Moines, Iowa. The investor wants to see data that will give a better sense of Citibike usage based on time, trip duration and gender. 

## Results
The following seven visualizations are included in the analysis of the NYC Citibike Data and displayed on a Tableau Public story [link to dashboard] (https://public.tableau.com/app/profile/leslie.scherger/viz/book3_16322828984610/NYCCitiBikeRideData#1 "link to dashboard")

### User Trips by Gender by Weekday
The heatmap for user trips by gender by weekday shows the largest concentration of user trips is with male subscribers on Thursdays and Fridays. There seem to be a low concentration of female customer trips during the weekdays and unknown gendered subscribers any day of the week (where there might be missing data.) It is important to take away that the most trips seem to be taken by subscribers, particularly male subscribers.

### Trips by Gender (Weekday per Hour)
The heatmap for trips by gender by weekday per hour shows a similar pattern for females and males, but there is darker shading, i.e. larger concentration of trips, taken by males. The highest concentration of stoptimes (roughly 10,000 or 15,000 trips) taken by females occurs around the 5 PM or 6 PM hour on Mon, Tue and Thu. The highest concentration of stoptimes taken by males (roughly 25,000 - 30,000) also occurs around the 5 PM or 6 PM hour on Mon, Tue and Thu. Both genders show higher concentraions of stoptimes around 7 AM to 9 AM, as well.

### Trips by Weekday for Each Hour
This chart shows a heatmap of stoptimes by weekday for each hour. The heatmap shows a darker area with higher trip numbers, around 20,000 between 10 AM and 5 PM on Saturdays and Sundays. On weekdays, there are higher concentrations of stoptimes occurring around 6 AM to 9 AM, and 5 PM to 7 PM, where we see the highest stoptime counts (almost up to 44,000 trips). The lowest trip counts occur from 11 PM to 6 AM daily (only about 360 rides).

### Checkout Times by Gender
There is a peak in number of bikes with checkout times around 10-15 minutes for males (~ 107K bikes), females (~35K bikes), and in unknown gender (~8K bikes). After checkout times of 10-15 minutes, the number of bikes rapidly declines, reaching close to 0 bikes around 50 minutes. Tripdurations over 1 hour also have close to 0 bikes, throughout checkout times in the second and third hours. There may be evidence here to suggest that people are taking citibikes out for tripdurations less than 1 hour, with most rides having around 10-15 minute checkout times. 

### Checkout Times for Users
There is a peak in number of bikes with checkout times around 10 or 15 minutes (147K bikes). There are around 35K bikes that had checkout times only slightly longer than 0 minutes, and the number of bikes increases with checkout times growing to 10 minutes. Checkout times greater than 15 minutes show substantially less number of bikes, with less than 3 K bikes having checkout times greater than 50 minutes. The number of bikes with checkout times into the 1st or 2nd additional hour looks to be under 1000, decreasing with checkout time increases. 

### Gender Breakdown
After converting number coded genders into strings with gender identities, the citibike rider gender breakdown was visualized in a pie chart. The pie chart shows that MALEs represent over half of citibike riders, and females around 25% of bike riders. About 1/6 of the riders are identified as 'UNKNOWN' gender. I included this gender breakdown chart because it gives insight into "Trips by Gender (Weekday per Hour)," "User Trips by Gender by Weekday" and "Checkout Times by Gender."

### Bike Repairs
This treemap gives us an idea of how often the bikes are used. Each bike id is represented by a spot on the map, which is darker and larger if there is a higher ride count for that bike. From this map, we can click on the bikeids in the top left corner (which are darker and larger) to identify the bikes that have most uses, which may need to be repaired based on their usage. This map is useful to Citibike planners, who can get a sense of how much use each bike gets and the amount of upkeep they can expect.

## Summary
After creating multiple visualizations in Tableau to learn about Citibike data, there are several takeaways that are evident, which can be used as starting points to design a bike sharing business in Des Moines, Iowa. First, the majority of users are subscribers, and most trips are taken by people identifying as male. Most trips last for 10 to 15 minutes, and are taken on weekdays around 7-9 AM or 5-7 PM or during daytime on the weekends. Based on the number of trips taken, we can gather that many people may be taking citibikes for trips to and from work, or to exercise before or after normal working hours (assuming a typical workday of 9-5). Many bikes have around 100 - 400 uses, which may help the new business prepare for bike maintenance routines. To continue analyzing the Citibike data in order to potentially start a similar program in Des Moines, there are other data associations that may be useful to visualize. For the first additional visualization, we should look into the average trip duration in distance, which can be found by using the start and end station coordinates. We could see how this is impacted by other factors, such as time of day or gender. For the second additional visualization, we should look into distances traveled by each citibike id, which could give us additional insight into expected repairs for bikes; for instance, bikes might need to be repaired after a certain mile milestone. By analyzing distances, we can fill in missing information about not only the users, but also, the bikes. 
