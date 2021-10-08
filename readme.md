# # Bike Sharing Data Exploration
### by Islam Mohamed


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

There are 183,412 individual rides data in the dataset with 16 features, that can be summarized as following;

- Time; Trip Duration in seconds, Start Time, End Time
- Departure and Destination; Start Station, End Station (ID, Name, Coordinates)
- Bike; ID
- User; Type, Birth Year, Gender

I'm most interested in figuring out what features are best for predicting the number of trips taken. The feaetures of the dataset we'll be exploring are;

- The trip duration
- The trip start time (summarized by day, weekday, and hour)
- The user demographic data (subsription type, birth year, and gender)


## Summary of Findings

The following findings can be fairly made from the exploration detailed above;

#### Average bike ride duration is less than 10 mins
As observed, the ride duration has a long-tailed distribution, with a lot of rides on the low duration end, and few on the high end. When plotted on a log-scale, the duration distribution is unimodal and skewed right, with most trips having duration around 500 seconds

#### Most rides are taken during weekdays
Trip Date distributions show that lower trip count was observed on weekends and higher trip counts were happening during weekdays with Thursday being the highest. Weekend engagement is almost 50% of that of an average weekday.

#### Bike-sharing also has rush hours
On another hand, trip distribution along the day is bimodal with one peak at **8:00 AM** and another at **05:00 PM**

#### Bike riders are mostly young males, but strong rides aren't
As observed, 75% of riders are males, and that most trips are taken by people in their late twenties and early therties (birth year 1988-1994). However, longer trips are made by females and other genders than males.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the trip time (day and hour) and user data (gender and subscription type) on the trip count and duration. Starting by the distributions of the trip durations and trip date. Then the relationship between them. Afterwards, I introduce the user data features in relation to the main features. All plots are polished by setting appropriate axes limits, titles, ticks, and selecting colors.