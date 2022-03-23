
## Project-01: Exploratory Data Analysis on MTA Turnstile Data:
This is the first project for the Metis Data Science Bootcamp, where we perform Exploratory Data Analysis (EDA) on the MTA turnstiles data.

- The target market are commuters who use the Metropolitan Transportation Authority (MTA) system since commuters are highly likely to use citibike in the morning to go to their office. In order to increase the user base, advertisements would be posted in high-traffic MTA stations. Users would then be sent push notifications from the app to prompt them to get daily, three-day, and annual passes citibike or renew their subscriptions, making Citi Bike a great option for commuters and locals alike.

## Analytical Approach
Criteria for Choosing MTA Commuter Stations
The publicly available MTA turnstile data from September 2021 to December 2021 was analyzed to determine the top ten stations that would garner the highest advertisement exposure to daily commuters. There were two criteria that were used to pinpoint these particular commuter stations:

- 1- High exit rate during the morning commute hours.
- 2- High entry rate during the afternoon and evening hours.
 - These two criteria would differentiate MTA stations with a high volume of commuter traffic from the other MTA stations.

## Goal:
- What are the busiest stations?
- What are the best time to prompt app users to get a citibike membership?

## Data:
- Data for MTA obtained from http://web.mta.info/developers/turnstile.html.
- Data for citibike obtained from https://s3.amazonaws.com/tripdata/index.html

## To do:
- High exit rate for top 10 busiest MTA stations in the morning
- High entry rate for top 10 busiest MTA stations in the afternoon or evening
- Finding the top 10 busiest citibike stations
- Identifying the busiest hours of citibike stations.

## Outcome:
- Post advertisements in high traffic MTA stations
- Encourage purchases through push notifications with discounts for citibike stations at peak hours


## The Methods and Tools:
#### Data ingestion and storage:
- Pandas
- SQLite
#### Data cleaning and manipulation:
- Python Libraries: Pandas, Numpy
#### Presentation tools:
- Matplotlib
- Seaborn


#### Getting ideas from some other related works such as:
- https://github.com/Anumala89/Citi-Bike-Analysis
- https://fitriwidyan.medium.com/nyc-citi-bike-trips-data-analysis-a07a1db9c1be
- https://rpubs.com/Ansh_Ji/citibike
- https://github.com/maxmelnick/mta_subway_analysis/blob/master/mta_subway_analysis.ipynb
- https://par.nsf.gov/servlets/purl/10113034
