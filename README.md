# Fordgobike Trip Data Exploration
## by Sarah Irungu

## Dataset

The data included in the bike share trip dataset was collected during the month of February 2019. It has more that 170k rows and 16 variables. It includes duration of a trip, start and end time of trips, among other variables. Some rows and columns were removed due to missing data and outliers.


## Summary of Findings

The trip duration has a normal unimodal distribution. Subscribers take less trip duration compared to customers. The highest average duration of trips is between midnight and 5 a.m. 

Majority of bike users are aged between 20 and 39 years i.e. birth year range of 1989 to 1999. On weekdays  bike usage is at peak between 5 a.m and 10 a.m and 3 p.m to 8 p.m and on weekends the peak is between 10 a.m and 3 p.m.


## Key Insights for Presentation

I focus on hour of day, day of week, and their relationship with trip duration. I also include birth year. I first introduce the distribution individual variables, main variable of interest - trip duration - which I used histogram and log scale plotting. I follow by plotting birth group year (ages) using a countplot. 

I then introduce relationship variables. I used a violinplot to show the relationship between the days of week, a categorical variable vs hour of day. I then use a line plot to make a sort of time series, trip duration vs hour of day. Lastly, I use the point plot to show the relationship between 3 variables - 2 categorical and 1 numerical - day of week vs trip duration vs user type.
