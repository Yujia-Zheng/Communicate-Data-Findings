# Communicate-Data-Findings
Analysis of Ford Gobike usage data
# Univariate Exploration:
In the univariate exploration, I focus on how different factors contribute to the number of rides. Therefore, I mainly use histograms to investigate the relationship between ride amounts and different variables. 
1. For ride duration, its distribution is skewed severely to the right. The vast majority of the rides are under 30 mins, and the longest ride is almost 24 hrs. 
When plotted on a log-scale, and zoom into the 0-2000 seconds range, the distribution is symmetrical, with the peak locating at around 500 seconds. 
2. For the members' birth year, the distribution is skewed to the left, meaning there are more younger members. The most concentrated years are around 1990.
3. There are several stations that are much busier than the average. The busiest two stations are No. 58 and No. 67. 
4. In terms of riders' gender, there are significantly more riders who identify as male than the riders identify as female or other. 
5. In terms of user type, the vast majority of the rides are for subscribers. Customers only contribute to a small fraction of total rides. 
6. There are much fewer rides on Friday and Saturday, almost only half of the other days.
7. As for both start hours and end hours, there are two peaks throughout the day: around 8am and 5pm. There are only very few rides during between midnight and 6am.

# Bivariate Exploration:
In the bivariate exploration, I focus on how different factors affect the duration of rides. I use bar plots and scatter plots. 
1. There is no correlation between ride duration and the rider's age. 
2. Even though the male group contributes the largest number of rides, they have shortest average ride duration. The members who identify as "other" gender ride the longest on average, but their ride durations also vary the most. 
3. Similarly, although subscribers contribute the vast majority of the rides, their average ride duration is much shorter (less than 1/2) of the average ride duration of customers. 
4. The rides during the late night--from midnight to 3am--have longer average duration and larger standard deviation than the rides during other hours. 

# Multivariate Exploration:
1. I break down the riders by gender and user type, and the result shows that the duration of rides and the riders' age are fairly consistent throughout different groups of riders.
2. I then investigate how the rider age and ride duration might change throughout the week, and the result shows that their distribution remain consistent throughout the week.

# Conclusions:
1. Although members of different age have different number of rides and ride duration, the relationship of member age and ride duration is not impacted by rider type, gender, and day of the week. 
2. The number of ride and ride duration, on the other hand, are affected by a number of different factors. 
