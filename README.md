## Module-18-Challenge

## Description

### As the new lead analyst for the New York City Bike program I have been tasked with finding 2 unexpected phenomena and I had decided to look at 2 years of data from the CitiBike Trip History Logs starting April 2021 - March 2023, but due to publishing difficulties had to reduce this down to October 2022-March 2023.

### Created by Sandra Botica

## Acknowledgements

**Data sourced from NYCOpenData**

https://data.cityofnewyork.us/NYC-BigApps/Citi-Bike-System-Data/vsnr-94wk

**Citi Bike System Data**

https://citibikenyc.com/system-data

**Citi Bike trip history data**

https://s3.amazonaws.com/tripdata/index.html

 - 6 csv files used from 202110-citibike-tripdata.csv through to 202303-citibike-tripdata.csv 


## Technologies Used

 - Python notebook
 - Tableau

## Getting Started

1. On my desktop I have saved a file <csv_joining.ipynb>
 - In this notebook the 6 csv files were combined.
 - The columns "started_at" and "ended_at" were converted to datetime.
 - A column for "trip duration" was added. Subtract the time "started_at" from the time "ended_at". This column was then converted to an integer.
 - I was advised it was not required to show this in github, especially when 24 large files in a folder are associated with it.

2. Click on this link to see the tableau visualisation.

# 

3. Open the <citibike_write_up.md> for an explanation about this analysis.

Enjoy marking!
Sandra
