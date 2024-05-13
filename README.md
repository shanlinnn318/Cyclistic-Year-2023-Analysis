# Cyclistic-Year-2023-Analysis
Google Analytics Case study: How does a bike-share navigate speedy success? The aim of this case study is to thoroughly examine the present business landscape, identify areas for improvement and design a new marketing strategy to maximize the number of annual memberships, thus leading the way for the company's future success.

## Dashboard Link
https://public.tableau.com/views/CyclisticYear2023Analysis/BikesTypesin2023?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link


##  Steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act

### Ask
#### 1. Define the problem: Design a new marketing strategy to maximize the number of annual memberships, thus leading the way for the company's future success

#### 2. Stakeholders: - 
i. Lily Moreno: The director of marketing and manager
ii. Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data
iii. Cyclistic executive team: The detail-oriented executive team that decide whether to approve the recommended marketing program

#### 3. Question: - 
How do annual members and casual riders use Cyclistic bikes differently?


### Prepare

#### Dataset Link
https://divvy-tripdata.s3.amazonaws.com/index.html

#### Dataset description
This dataset tabulates ride_id, bikes types, starting and ending time, their starting and ending stations (names, longitude and latitude measures) and customer account types. I will focus on using 2023 data for this case study.
The data has been made available by Motivate International Inc. under license. For more details, you may refer to https://divvybikes.com/data-license-agreement. 

#### Variable definitions

ride_id - This combination consists of 14 characters including numbers and letters. Example: C9BD54F578F57246, CDBD92F067FA620E

rideable_type - Types of bikes: electric_bike, classic_bike and docked_bike

started_at - In format of MM/DD/YYYY HH:MM:SS AM/PM

ended_at - In format of MM/DD/YYYY HH:MM:SS AM/PM

start_station_name - Name of starting station

start_station_id - ID of starting station

end_station_name - Name of ending station

end_station_id - ID of ending station

start_lat - Latitude of starting station

start_lng	- Longitude of starting station

end_lat	- Latitude of ending station

end_lng	- Longitude of ending station

member_casual - Types of members: Member or Casual

### Process and Analyze
BigQuery has been employed to efficiently handle the data processing task, Microsoft Excel is unable to accomplish due to its limitations with large datasets.

1. Combine Data: https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/blob/main/Cyclistic_Combine%20data
2. Data Exploration: https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/blob/main/Cyclistic_Data%20Exploration
3. Data Cleaning: https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/blob/main/Cyclistic_Data%20Cleaning
4. Data Analysis: https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/blob/main/Cyclistic_Data%20Analysis
   
For more details and results, you may refer to the links above.

# Share
To answer the question "How do annual members and casual riders use Cyclistic bikes differently?" that mentioned earlier, I have prepared 5 dashboards to answer this question.

1. This visualization shows bikes types used in 2023 by two groups of users.

![image](https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/assets/113488502/aeb6d919-e1b5-4bc6-8a89-f8dd2c40a946)
The outcome reveals that there are currently 2,738,451 active members, representing nearly 64.53% of the total user base, while the remaining 35.47% consists of casual riders. Classic bike has the most popularity among users and followed by the electric bike. However, only 1.78% of users use docked bikes.

2. Visualization shows the total number of trips by month, day and hour.
![image](https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/assets/113488502/5a3b0847-0f7b-4ccf-b432-2a66cc644924)
For monthly data, both casual and member users demonstrate comparable patterns, showing increased travel during the spring and summer months (MARCH until AUGUST) and decreased activity in the winter (DECEMBER until JANUARY). Looking at the graph that indicates number of trips by day, casual and member riders shows opposite patterns. Members tend to make their ride on weekdays and casual users prefer to make their journey on weekend. When examining hourly data, a clear trend emerges: both types of users overwhelmingly prefer riding during the morning at 8am and in the evening at 5pm.

3. Visualization indicates average ride duration in 2023.
![image](https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/assets/113488502/a043c5e8-d93e-4b58-8b40-aac4e6a2711a)
As highlighted in the narrative of the second visualization, there's a notable uptick in ride activity for both types of users during the spring and summer months. This trend extends to the average ride duration by month (Above 20 minutes), with a substantial increase observed over the same period. And when we look at average ride duration by day, we can observe that both casual and member riders will spend more time for riding. For hourly data, between 10 am and 2 pm, users tend to embark on longer journeys during the day. Conversely, from five to eight in the morning, their trips are typically shorter in duration.

4. This symbol map shows the total trips at starting stations in 2023. 
![image](https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/assets/113488502/e1751338-cce4-4ba2-9ff5-9407780c112f)
Streeter Dr & Grand Ave sees the highest volume of riders starting their rides. Streeter Dr & Grand Ave is situated nearby to Jane Addams Memorial Park and the apartment building Lake Point Tower. Casual riders predominantly kick-start their trips from stations adjacent to museums, parks, beaches, harbors, and aquariums, while members opt to commence their journeys from stations proximate to universities, residential areas and commercial districts.

5. This symbol map shows the total trips at starting stations in 2023. 
![image](https://github.com/shanlinnn318/Cyclistic-Year-2023-Analysis/assets/113488502/eb256024-39e7-48b6-b9b4-b96e5685b09a)
Most of the riders chose to end their journey at Clark St & Elm St. Casual riders often conclude their journeys near parks, museums, and recreational areas, while members tend to end their trips in proximity to residential areas and commercial districts.

    

