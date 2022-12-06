# Tableau Project: bikesharing 
## Overview
For this project, I was tasked with downloading the csv file of 2019_citibike_trip_dataset for the month of August. Then complete two technical analysis on the data and write this report. The first analysis is that I am to clean up the data using pandas, more specifically, to change the "Trip Duration" column's datatype to datetime. I did so by importing the data from csv file to a dataframe, changed the "Trip Duration" column to datetime, and then export the dataframe as a csv file. The second part of the analysis is for me to create visualization for the Trip Analysis on Tableau. For this analysis, I created five visualizations on Tableau. I placed the visualizations into two dashboards and made a story out of them. 

[Link to the Tableau story site!](https://public.tableau.com/views/TripdataStoryAnalysis/NYCCitibike?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Results
### Checkout Times for Users
![Checkout Times for Users](/Images/CheckoutTimesforUsers.png)
This worksheet shows us the trends between the number of bikes that are checked out for use vs how long they have been checked out for. As shown in this image, most bikes are checked in for around five minutes. 

### Checkout Times by Gender
![Checkout Times by Gender](/Images/CheckoutTimesbyGender.png)
This worksheet shows us the trends of genders (male, female, or unknown) between number of bikes that are checked out for use vs how long they have been checked out for. The trends are similar to the above worksheet (Checkout Times for Users), however, we see that males use city bikes approximately four times more than females, and ten times more than unknown genders. 

### Trips by Weekday per Hour
![Trips by Weekday per Hour](/Images/TripsByWeekdayPerHour.png)
This worksheet shows us a heatmaps that also shows the number of trips occurs for each day of the weekdays. According to this data, we see that on Thursday 5pm - 6pm, it is the most active. 

### Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](/Images/TripsByGender(WeekdayPerHour).png)
Similar to "Trips by Weekday per Hour" worksheet, this work sheet does the similar except, it creates individual heatmaps for each genders. From the three available heatmaps, we see that males has the highest occurance for renting city bikes. 

### User Trips by Gender by Weekday
![User Trips by Gender by Weekday)](/Images/UserTripsByGenderByWeekday.png)
This heatmap tells us the same information as the above two heatmap worksheet, however, with the addition of what kinds of cosumers often pertake in renting city bikes. From the heatmap, we see that subscribers are the most active in terms of renting city bikes. 

### User Data 
![User Data)](/Images/UserData.png)
Lastly, this is a simple dashboard consisting of two worksheets, namely: Number of Rides, and User Types. This dashboard gives us an idea about how many riders participated in renting city bikes and how many among them are normal customers and subscribers. We see that 3/4th of the rides that occurred were by the subscribers. 


## Summary 
In addition to the visualizations provided, we can add few more visualizations. One of the most important visualization that can be added for future is a "Top Starting Location" map. This map will help the compnay prepare beforehand by having enough bikes to be rented out. Another important visualization that could be added is making a tree chart that displays bike utilization. This is quite important as it helps the company be aware of the bikes that may require maintenances. 
