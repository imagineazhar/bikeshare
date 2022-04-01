# Case Study: Bike-share Company
In this case study, I will perform data analysis for a fictional bike-share company (Cyclistic) in order to help them attract more riders. 

## Task Statement:
Analyze historical data to find differences between annual members and casual riders. Based on the analysis provide three recommendations for marketing strategies aimed at converting casual riders into annual members.

## Data Prep:
I will use Cyclistic’s historical trip data to explore how different customer types are using bikes. [Download the previous 12 months of Cyclistic trip data
here](https://divvy-tripdata.s3.amazonaws.com/index.html). 


>  The datasets have a different name because Cyclistic is a fictional company.The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement).) This is public data that I can use for analysis. 


```
./data/
    ├── Trips_2019_Q2.csv
    ├── Trips_2019_Q3.csv
    ├── Trips_2019_Q4.csv
    └── Trips_2020_Q1.csv
```
#### Data Description:
This dataset consists of four files containing data about a complete quarter.
Each file consists of one million bike rides and related features such as rental id, start and end time, bike id, trip duration, and some demographic information about the rider. 
In this dataset, each example corresponds to one single ride.

_The naming convention used in each file is not standardized. We'll have to develop a consistent naming convention for features._
