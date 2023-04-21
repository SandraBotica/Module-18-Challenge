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
 - Tableau Public

## Getting Started

1. Open the <combining_csv_files_12_months.ipynd> 
    In this notebook the 24 csv files were combined.
    The columns "started_at" and "ended_at" were converted to datetime.
    A column for "trip duration" was added, based on subtracting the "started_time" from the "ended_at" time. 
    This column was then converted to an integer.

2. Click on this link to see the tableau visualisation.


### This visualisation aims to inform CitiBike and City Officials about usage of bikes in NYC from April 2021 to March 2023.

### There are 2 parts to this story.
## Part 1 - First 4 Dashboards.

### What can we learn about ridership trends based on:

### - The **Total Rides** Per year, season, month, day of the week or hour of the day.
### - The **Total Rides** registered as a member or casual rider.
### - The **Total Rides** using either a classic-bike, e-bike or docked-bike.

## Part 2 - Last 2 Dashboards.

### What can we learn about Stations based on:

### - Total Rides per Station.
### - Average Trip Duration Per station.

    P