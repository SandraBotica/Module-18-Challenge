## Module-18-Challenge

## Description

### As the new lead analyst for the New York City Bike program I have been tasked with finding 2 unexpected phenomena and I have decided to look at 2 years of data from the CitiBike Trip History Logs starting April 2021 - March 2023.

### Created by Sandra Botica

## Acknowledgements

**Data sourced from NYCOpenData**

https://data.cityofnewyork.us/NYC-BigApps/Citi-Bike-System-Data/vsnr-94wk

**Citi Bike System Data**

https://citibikenyc.com/system-data

**Citi Bike trip history data**

https://s3.amazonaws.com/tripdata/index.html

 - 24 csv files used from 202104-citibike-tripdata.csv through to 202303-citibike-tripdata.csv 


## Technologies Used

 - Python notebook
 - Tableau

## Getting Started

1. Open the <combining_csv_files_12_months.ipynd>
 - In this notebook the 24 csv files were combined.
 - The columns "started_at" and "ended_at" were converted to datetime.
 - A column for "trip duration" was added. Subtract the time "started_at" from the time "ended_at". This column was then converted to an integer.

2. Click on this link to see the tableau visualisation.


### This visualisation aims to inform CitiBike and City Officials about usage of bikes in NYC from April 2021 to March 2023.

### There are 2 parts to this story.
## Part 1 - First 3 Dashboards.

### What can we learn about ridership trends based on the **Total Rides** per Year, Season, Month, Day of the Week or Hour of the Day.

## - Dashoboard 1 provides insight into the Number of Total Rides for the 2 years and what percentage of that Total Rides does each year contribute. The monthly bar chart is colored according to season and reflects the seasonal variations of ridership. 

## - Dashboard 2 provides insight into the Total Rides per Day of the Week and Hour of the Day, based on the Season.

## - Dashboard 3 provides insight into the Average Trip Duration per Month, Season and Day of the Week.

 - The first dashboard indicates to Citibike that ridership is increasing in all months from 2021 to 2023, except in October and December from 2021 to 2022. Monitoring these growth trends will assist Citibike to make certain they have enough bikes and stations to account for this growth trend. Citibike may also need to meet with City Officials to discuss Town Planning to accomodate this growth.
 - The first two Dashboards provide Citibike data to consider when planning bike or station safety maintenance, which might best be planned during off-peak periods.
 - The first two Dashboards provide Citi officials data to consider for safety/awareness campaigns. They may consider advertising leading into peak seasons, months, days of the week or hours of the day to make the public aware of the increased ridership in the City of NY.
 - The third Dashboard provides Citibike data about the average trip duration.

## Part 2 - Last 2 Dashboards.

### What can we learn about Stations based on **Total Rides** per Station and if the rider is a member or casual rider and what type of bike they are riding.

## - Dashoboard 4 provides insight into the 10 Start Stations with the highest number of Total Rides for the 2 years. Two bubble charts indicate what number of Total Rides at that Start Station are a casual or member rider and what type of bike they are riding.

 - Consider that a similar Dashboard could look at the 10 Start Stations that recorded the least number of Total Trips, or an analysis on the top and bottom 10 End Stations.

## - Dashboard 5 provides a map of the Total Rides per Station, size and color based on the number of Total Trips.

 - The 4th Dashboard could assist CitiBike determine which Stations use which type of bike and adjust which bikes they offer based on demand. Citibike could also consider increasing the use of the less popular type of bike, by offering reduced fees to encourage growth of bike usage. Citibike could also offer reduced fees for Stations that don't have high casual usage, so as to atleast increase Total trips and revenue, especially if bikes are available at Stations.
 - The 4th Dashboard could encourage Citi Officials to offer incentives for businesses or residents near specific Stations. Offering incentives that contribute to a carbon reducing tally for a ZIP CODE, which then might be rewarded with discounts to local industries.
 - The 5th Dashboard that maps total trips based on every start and end station can inform Citibike which areas they may need to provide more bikes and Stations that may require increased campaigning to encourage use of CitiBikes.