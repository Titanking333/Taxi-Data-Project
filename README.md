# New York City Taxi and Limousine Commission (TLC) Data Analysis

### Since 1971, TLC has been regulating and overseeing the licensing of New York City's taxi cabs, for-hire vehicles, commuter vans, and paratransit vehicles.
### It data gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. In order to improve the learning experience and shorten runtimes, a sample was drawn from the 113 million rows in the 2017 Yellow Taxi Trip Data table.

This project collected and analyzes trip data from the New York City Taxi and Limousine Commission (TLC) to satisfy the following goals.
## Goals:

1. Understand trip patterns, durations, and fares.
2. Identify key insights about passenger behavior and payment methods.
3. Apply statistical methods to uncover relationships between variables

## Project Objectives:
(1) Develop a model that helps estimate taxi fares before the ride, based on data that TLC has gathered.
(2) Develop another model to help Taxi drivers generate more revenue, by predicting wheather a customer is a generous tipper or not.

## Questions asked:
1.	How do the rides spread throughout the time of the day and when do most rides take place on any typical day?
2.	How does the total income of the year spread during the time of day and its average on every given section of the day?
3.	How much income and how many rides are made per day on an average?
4.	What is the average monthly performance, in term of income and passenger rides?
5.	Can we see trend of rides and total amount earn for the whole year?
6.	What are the top 4 drop off locations that rolled in the big spenders/ tippers?
7.	Do costumers paying with credit card pay a higher fare amount than those using cash?

## Processes Implemented:
1.	A fair amount of data cleaning was implemented to change some columns’ data type, remove some columns and rearrange their order on the table.
2.	 Constructing of more columns using the existing ones was also implemented.
3.	EDA was carried out to understand the elements of the data and full out oddities, which then required more data cleaning.
4.	Visualisations like bar charts using python was used to paint images of what the numbers and groups were saying.
5.	Power BI greatly enhanced those said images to a greater degree. - <a href="https://github.com/Titanking333/First-Year/blob/main/Taxi%20data%20Insight%20Report.pbix">Taxi data Insights</a>
6.	A/B testing was carried out to test an assumption of two groups.
7.	Regression models were constructed to predict future fare amount based on the available data.
8.	Classification models were also constructed to predict likely generous customers.

### Insights:
#### 1.	 For the year – 2017, a total of 22,699 rides was recorded; 237 of the records are assumed to be moment when taxi driver cruise around the city for customers, leaving behind records of 22,462 rides with at least 1 passenger for each ride.

#### 2.	75% of customers request for a ride between Morning (6 am) to Evening (8 pm), with average fares of $248, $250, and $240 respectively during those times of the day.


#### 3.	With Morning pickups raking in a total of $ 93, 000 for the year and an average of $ 255 daily, Afternoon - $ 95,000 and an average of $ 261, and Evening - $ 89,000 and an average of $ 243.

#### 4.	An average of 62 rides per day with an income of $997, and an average of 1872 passenger per month with an average distance travelled per month being 5503 miles.

#### 5.	The month of March, October, April and May are the months with the most rides reprehensively, each holding a total amount of rides of at least 2000 rides. From the line graph in the Jyputer Notebook, there are a few interesting things to speak of;    
       a.	From March to April, total income declines while ride durations significantly increase.
       b.	Come in May, the duration of rides steadily decreases while the amount of income generated climbs up; maintaining somewhat of a stable income through June, before steadily                 dropping as July approaches.
       c.	The months (March and October) seem to be the two separate period of the year when the number of rides increases significantly without the concern of the previous month       performance.
       d.	Starting June, the duration of rides makes a boorish trend to November; when it spikes up without any pull back till December. Making November and December the months with the highest duration of rides despite 8th and 7th position in term of total number of rides per month.

#### 6.	For the month of March, the three most reoccurring Dropoff location are ID: [236, 170, 237].
        a.	For the month of October – ID [236, 161, 237].
        b.	For the month of April – ID [236, 161, 237].
        c.	For the month of October – ID [142, 237, 161].
        d.	This is influenced by the Standard Rate ( 1 ) applied at these drop-off locations.

#### 7.	Customers indeed pay a higher fare amount than those that pay with cash, so a system should be put in place to capitalise on that.

#### 8.	Approximately 34% of the passengers tipped 20% or more the amount of their total amount they pay at the end of the ride.

## Conclusion
This analysis of the 2017 New York City Taxi and Limousine Commission (TLC) dataset provides critical insights into taxi ride patterns, fare estimation, and customer tipping behavior.
1.	Peak Ride Times and Revenue Trends:
o	Most taxi rides occur between 6 AM and 8 PM, accounting for 75% of total rides.
o	Revenue is highest during the morning, afternoon, and evening, averaging $248–$255 per ride during these times.
o	The months of March, October, April, and May see the highest number of rides.
o	Income trends show a decline from March to April, followed by a steady increase in May, then a dip in July.
o	November and December have the longest ride durations despite lower ride counts.
2.	Drop-off Locations and Spending Patterns:
o	Certain drop-off locations, such as IDs 236, 161, and 237, consistently appear in high-revenue months.
o	The standard rate applied to these locations impacts overall fare amounts.
3.	Payment Methods and Tipping Behaviour:
o	Customers paying via credit card tend to pay higher fares than those using cash.
o	34% of passengers tip 20% or more of their total fare, highlighting a segment of generous tippers.

Dataset Source: Google Advanced Data Analytics Course - <a href ="https://github.com/Titanking333/First-Year/blob/main/2017_Yellow_Taxi_Trip_Data.csv">Dataset</a>

Note: This project's dataset was created for pedagogical purposes and may not be indicative of New York City taxi cab riders' behaviour.


