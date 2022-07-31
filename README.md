# Citibike Bikesharing

## Overview
The purpose of this project is conduct a statistical analysis to be included in a business proposal for a bike-sharing program in Des Moines, based off of the bike-sharing data gathered from the program run by Citibike in NYC.  The analysis was conducted on Citibike's August 2019 bike-sharing data and began with using Python's Pandas library to convert the tripduration column into a date-time format.  The data file was then uploaded into Tableau where 7 visualizations were created to tell a story of the analysis of the NYC Citibike program.  The images folder in this repository contains the screen shots of each of the data visualizations and here follows the Link to Tableau Story - NYC CitiBike Challenge: https://public.tableau.com/app/profile/fredrica.stanley/viz/NYCCitiBikeChallenge_16592802481960/CitiBikeBikesharingDataNYC08-2019 

## Results
The original data file from Citibike displayed the tripduration column as an integer datatype, this column was converted to a datetime datatype to get the time in hours and minutes rather than in total number of seconds. The original file, python code used, and updated file are shown below:

![201908-citibike-tripdata](https://user-images.githubusercontent.com/103215123/182047442-60a95024-10ef-454b-a653-7b1afdd84a0d.png)

![converted_tripduration_df](https://user-images.githubusercontent.com/103215123/182047449-e960be62-0483-45fc-9189-4a1283872aa2.png)

![updated-201908-citibike-tripdata](https://user-images.githubusercontent.com/103215123/182047455-2fcad270-3c97-45e1-88c2-7f6febb99dda.png)


### Visualizations 

1. Gender Breakdown:
![gender_breakdown](https://user-images.githubusercontent.com/103215123/182047622-2a0f0f18-c3fa-4c29-9c6d-b30ab2de44d3.png)
This pie chart shows the gender breakdown of the Citibike users, the majority of Citibike users are male, with only approximately 25% female.  

2. Checkout Times for Users:
![checkout_times_for_users](https://user-images.githubusercontent.com/103215123/182047712-4fe10e90-4f81-425d-9649-f1a101c5f573.png)
This chart shows that the majority of bikes are checked out for less than 1 hour.  The filter can be used to isolate the hour of trip duration.  

3.  Checkout Times by Gender: 
![checkout_times_by_gender](https://user-images.githubusercontent.com/103215123/182047882-0f39c165-a8b0-4b99-a994-daf8d2057f6d.png)
This chart digs deeper into the checkout times of users and shows the checkout times broken down by user gender.  Male and female trip durations seem to follow the same pattern, most users using the Citibike bicycles for less than 1 hour. 

4.  Trips by Weekday per Hour:
![trips by weekday per hour](https://user-images.githubusercontent.com/103215123/182048079-8888cc33-1ce4-41d5-a133-e547f3338a21.png)
This is a heatmap showing the number of trips during an hour of start time and the day of the stop time.  The darker the color the more trips taken that weekday starting that hour. The cluster of dark orange areas seem to coincide with morning and evening weekday rush hour commutes. 

5.  Trips by Gender (Weekday per Hour):
![trips_by_gender_weekday_per_hour](https://user-images.githubusercontent.com/103215123/182048288-a642eb25-bce3-4fae-b659-0a26ab3fe24b.png)
This heatmap digs a little further into the analysis of most trips by weekday per hour by separating out this data by gender.  The male and female heatmaps show dark or higher amounts of bike trips on weekdays during standard rush hour commuting times. The unknown gender category actually shows more trips on weekend, Saturday/Sunday, daytime hours. 

6.  User Trips by Gender by Weekday:
![user_trips_by_gender_by_weekday](https://user-images.githubusercontent.com/103215123/182048416-daa18c68-42a1-4a31-9ea2-93b4054e3114.png)
This heatmap shows the number of trips taken by male, female, and unknown gender types and further shows how this data is separated by user type, either a 'Customer' or 'Subscriber'.  The most user trips taken on Citibikes were by Male Subscribers on Thursdays.  

7.  Top Starting Locations: 
![top_starting_locations](https://user-images.githubusercontent.com/103215123/182048564-270d0f6a-e785-4194-ab4e-7623a776a184.png)
This bubble chart shows the areas in which the most bike trips start from. 

8.  Top Ending Locations: 
![top_ending_locations](https://user-images.githubusercontent.com/103215123/182048567-4359d9eb-d192-4fbb-a6b8-432b92afdbf6.png)
This bubble chart shows the areas in which the most bike trips end.  

## Summary
The Tableau story visualizes the Citibike data showing how the Citibike program is used by riders in New York City.  
