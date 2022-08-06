<h1 style="font-weight:normal" align="center">
&nbsp; Case Study: Bike-share Company &nbsp;
</h1>

<div align="center">

&nbsp;&nbsp;&nbsp;
[![Linkedin Badge](https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/imagineazhar)
[![Twitter Badge](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/imagineazhar)
[![Instagram Badge](https://img.shields.io/badge/instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/grinch__101)
[![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:2muhammadazhar@gmail.com)
[![Medium Badge](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@imagineazhar)

</div>

In this case study, I will perform data analysis for a fictional bike-share company (Cyclistic) in order to help them attract more riders. 

## Task Statement:
Analyze historical data to find differences between annual members and casual riders. Based on the analysis provide three recommendations for marketing strategies aimed at converting casual riders into annual members.

## Data Prep:
I will use Cyclistic’s historical trip data to explore how different customer types are using bikes. [Download the previous 12 months of Cyclistic trip data
here](https://divvy-tripdata.s3.amazonaws.com/index.html). 


>  The datasets have a different name because Cyclistic is a fictional company.The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement).) This is public data that I can use for analysis. 
>  
#### Data Description:
This dataset consists of 12 files; each file contains data about a complete month. Each example corresponds to one single ride.
### Data Dictionary:
| **Name of Data Field**  | **Data Type** | **Description**                                                          |
|-------------------------|---------------|--------------------------------------------------------------------------|
| ride_id                 | int           | Identification number of trip.                                           |
| started_at              | Timestamp     | When a trip started                                                      |
| ended_at                | Timestamp     | When a trip ended                                                        |                                         |
| ride_length             | Timestamp     | How long a trip lasted.                                                  |
| start & end station     | geography     | start and end location                                                   |
| member_casual             | string        | Information about whether a rider was a subscriber or a casual customer. |
