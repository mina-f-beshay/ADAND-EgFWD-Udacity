# Ford GoBike Trips

## Dataset

There are 183,412 trips in the dataset (after data cleaning) mainly about the bike trips information such as trip duration and many member information like member age, gender and user type. The dataset can be downloaded from this link https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv 


## Summary of Findings

In the exploration, I found that the geolocation distribution of the stations is not symmetric, some stations are too near and some are too far. The most of the trips were made by the subscribers (90.5% of the number of trips) not the customers (9.5% of the number trips), but the customers made longer and farther trips than the subscribers. 
The most of the company members are males.
The most of the company members are young at the age of 30-35 years old.
The trip duration on average was about 5-10 minutes.
The trip distance on average was about 3 distance unit.
The distributions of the trip duration and trip distance are left skewed due to many outliers, the log scale helped in identifying them.
The trips on weekends are longer and farther than on working days.
More young female customers made rides for duration less than 10 minutes.
Subscribers usually made rides with fixed time about (11 mins) across all the age groups we have.
Customers are active on weekends, at hours from 10AM to 4PM but the subscribers are active on working days mainly at 8AM and 5PM.


## Key Insights for Presentation

For the presentation, I focus on just on the number of the trips, trip duration, trip distance and the member user type.

I highlight that most of the trips are made by the subscribers across the weekdays and hours. However, the customers have longer and farther trips. 
I focused also on the active hours for the customers are on weekends from 10AM to 4PM but for the subscribers, the active hours are on working days, specifically at 8AM and 5PM.  