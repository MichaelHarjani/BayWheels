# BayWheels Ridership Exploraiton
## by Michael Harjani

## How to view the presentation

> The easiest way to view the presentation is to download the 'presentation.slides.html' file and run on a web browser. 


## Dataset

> The data consits of 6,165,032 trips including start and end times and locations, the type of bike used, type of user, and other user and bike characteristics. While the dataset was in one of the given files, it has been altered several times as there was a change in format. The dataset can be found [here] (https://s3.amazonaws.com/baywheels-data/index.html) with some of the feature documentation available [here] (https://www.lyft.com/bikes/bay-wheels/system-data). As some have been renamed and altered, they are listed below.


duration - Duration of the trip in seconds
started_at - Start date and time of trip
ended_at - End date and time of trip

start_id - Start station id if available
end_id - End station id if available
start_name - Name of start station if available
end_name - Name of end station if available

start_lat - Latitude at start of trip
start_lng - Longitude at start of trip
end_lat - Latitude at end of trip
end_lng - Longitude at end of trip

start_city - city that the ride started, based off of longitudinal differences

distance - distance from start to end of trip in a straight line (in km)
speed - average speed from start to end of the trip (in kph)

user_type - Whether the user is a Member or Casual
bsfa - If the rider is in the 'Bike Share for All' program
user_class - separating out the BSFA subset of Members in user_type

bike_id - Unique interger identifier of each bike,
ride_type - Whether the bike was a docked or electric version

rent_method - What method the user used to rent the bike (App or Clipper)

start_date - started_at, but only the date
start_year - started_at, but only the year
start_hour - started_at, but the hour (0-23)
start_dow - started_at, but only the day of week (0-6)
start_yymm - started_at, but in year-month format (2020-04)
start_month - started_at, but only the month

dow - day of week in string form




## Summary of Findings

> In the exploration, I found that there was a different in how different users in different cities as as well as within the different users groups use the bikes differently. I also found the uneven distrubution of the three different user groups across the three cities. Lastly, I found that metrics such as population density, and the population's access to a vehicle are more important to the success of bikesharing in the city rather than just population. 


## Key Insights for Presentation

> For the presentation I focused on the basic stats about the rides before diving deeper into the situations that seemed to warrant questions as to why they would appear that way. At the end, I used data from outside to possibly explain certain user behaviours. 


