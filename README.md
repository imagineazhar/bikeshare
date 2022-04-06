# Case Study: Bike-share Company
In this case study, I will perform data analysis for a fictional bike-share company (Cyclistic) in order to help them attract more riders. 

## Task Statement:
Analyze historical data to find differences between annual members and casual riders. Based on the analysis provide three recommendations for marketing strategies aimed at converting casual riders into annual members.

## Data Prep:
I will use Cyclistic’s historical trip data to explore how different customer types are using bikes. [Download the previous 12 months of Cyclistic trip data
here](https://divvy-tripdata.s3.amazonaws.com/index.html). 


>  The datasets have a different name because Cyclistic is a fictional company.The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement).) This is public data that I can use for analysis. 
>  
#### Data Description:
This dataset consists of 12 files; each file contains data about a complete month.
Each file consists of features such as trip id, start and end time, trip duration, and some demographic information about the rider. 
In this dataset, each example corresponds to one single ride.

_The naming convention used in each file is not standardized. We'll have to develop a consistent naming convention for features.

### Data Dictionary:
| **Name of Data Field**  | **Data Type** | **Description**                                                          |
|-------------------------|---------------|--------------------------------------------------------------------------|
| ride_id                | int           | Identification number of trip.                                           |
| started_at              | Timestamp     | When a trip started                                                      |
| ended_at               | Timestamp     | When a trip ended                                                        |                                         |
| trip duration (seconds) | int           | How long a trip lasted.                                                  |
| start & end station     | geography     | start and end location                                                   |
| user type               | string        | Information about whether a rider was a subscriber or a casual customer. |
