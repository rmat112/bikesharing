# Bike Sharing
# Overview of the Analysis
Starting a new bike-sharing business in Des-Moines is under evaluation. For comparison, there is data available from a bike-sharing company in New York.
A few graphs and dashboards can help evaluate what to expect.
# Results
## 1. 
Use Pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes. Once the datatype is changed, the DataFrame is exported as a CSV file to use for the visualizations in the next step.

## 2.
The following questions are answered by creating visualizations in Tableau:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

## 3.
A story is created by putting together the information from the previous step. A link to the story is provided here: 
We are analyzing a daset frm New York citi bikeshare comapny for the month of August. This data will help us understand bikesharing needs in DesMoines.
Attached below are the screenshots of the story with a description underneath.


A key piece of data we need is the peak usage hours for the month of August. This will help us get a better idea of how many bikes we might need in Des Moines, as well as figure out during which parts of the day we'll need the most bikes. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that.
Based on the chart the top riding hours during August in New York city are between 5:00pm to 7:00 pm and the best time for bike maintenance is between 2:00 am and 5:00 am.

Understanding both when and where people use Citi Bike will help us plan our pilot in Des Moines. So we decide to find the top locations for starting a bike journey among Citi Bike customers. Along with this it would also help to see where people end their journey. This information is plotted on the symbol maps plotted above. As seen here, in order to create these maps we used the latitude and longitudes of the starting and ending locations of the bike trips. The number trips is represented by the size and color of the symbols. The most popular starting and ending locations are represented by bigger and darker symbols.

These graphs show the length of time that bikes are checked out for all riders and the length of time that bikes are checked out for each gender. As seen here, most riders checkout bikes for less than half hour. Also, number of male riders is much higher than female riders.

These graphs show the number of bike trips by weekday for each hour of the day and the number of bike trips by gender for each hour of each day of the week as heatmaps. These maps show high bike usage on weekdays around 8-9AM and between 5 and 6 PM, specially by male gender. Since pattern on saturday and sunday is different, this high usage indicates bike use for commute.

This heatmap shows the number of bike trips broken down by gender for each day of the week by each Usertype (customers or subscribers). This map reiforces the fact that majority users are males. It also informs that there are a lot more subscribers than one time customers who use bikeshare.


# Summary
Below is a summary from the analysis of the New York Citi bikeshare company data:
A large population of metropolitan areas uses bike sharing as a means of commute due to difficult driving and parking conditions. This is indicated by the fact that most bike usage occurs on weekdays durnig the morning and evening commute hours. Also, the top trip starting and ending locations are within the Manhattan area where all office locations are. It is also worth noting that majority riders are male and are subscribers.
In order to get more information I would visualzie
- Most number of trips taken by each gender per location
- Trip durations each day of the week