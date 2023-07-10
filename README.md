# Bike Sharing project
Portfolio Project to showcase skills

## Scenario
As a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago, my role is crucial in achieving the company's future success. 
The director of marketing has emphasized the importance of maximizing the number of annual memberships. To accomplish this goal, our team aims to gain a deep understanding 
of the distinct usage patterns between casual riders and annual members of Cyclistic bikes. Armed with these insights, we will develop a comprehensive marketing strategy 
aimed at converting casual riders into loyal annual members. However, before presenting our recommendations, they must be supported by compelling data insights and presented 
through professional data visualizations. The final approval of our recommendations lies with Cyclistic executives, emphasizing the significance of thorough analysis 
and impactful visualizations in our work.

## Ask Stage: Business Task
Understand how annual members and casual riders use Cyclistic bikes differently to design a marketing strategy aimed at converting casual riders into annual members.

## Prepare Stage: A description of all data sources used
All rides are stored in .csv files. Rides for each month are confined in zip files, which are all stored on the external server. 

After extracting all files, the structure of the database was revealed as the following: 

Variable Name | Description
------------- | -------------
ride_id | Unique identifier for each ride
rideable_type | Type of rideable vehicle (e.g., electric_bike, classic_bike)
started_at | Start time of the ride
ended_at | End time of the ride
start_station_name | Name of the station where the ride started
start_station_id | Unique identifier for the starting station
end_station_name | Name of the station where the ride ended
end_station_id | Unique identifier for the ending station
start_lat | Latitude coordinate of the starting station
start_lng | Longitude coordinate of the starting station
end_lat | Latitude coordinate of the ending station
end_lng | Longitude coordinate of the ending station
member_casual | Indicates whether the rider is a member or a casual rider (Customers who purchase single-ride or full-day passes are referred to as casual riders, customers who purchase annual memberships are members)

