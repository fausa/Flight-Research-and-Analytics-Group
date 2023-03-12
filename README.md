# Flight Research and Analytics Group

### Authors: Annie Chan, Azucena Faus, Mohammad Mahmoudighaznavi
### Company Industry: Air Transportation
### Company Size: 3 (startup)
### GitHub Repository Link: https://github.com/fausa/Flight_Analytics

## Abstract:
The airline industry plays an important and critical role in the world’s transportation sector. VArious factors such as weather conditions, air traffic control, airport operations, etc., have the capability to directly and indirectly affect airline services, leading to delayed flights. Understanding the effects of such issues in advance would prepare airline operators for potential reasons of flight delays. 

## Problem Statement:
Although travelers know the propensity for canceled flights during the winter months due to weather, it is difficult to know when that likelihood is highest and what flight to schedule if travel is nonetheless required. Knowing what airline to go with if there is a high likelihood of cancellation would be useful.

## Goals:
We would like to provide customers with information regarding the likelihood of canceled flights due to weather, along with suggestions for which airlines would be best to go with, in case the likelihood is high. The airline recommendations would stem from customer satisfaction when they experienced canceled flights with those airlines, and the services they not only offer, but actually follow through with.

## Non-Goals:


## Data Sources:
One of the data sources comes from a relational database called Airline that contains US domestic flight information for January of 2016, along with information regarding canceled flights and whether those cancellations were due to weather. The second dataset was collected from Kaggle, which contains weather data for US airports for the years 2016-2021. This way, departure airport weather conditions can be added features for those flights that experienced cancellations due to weather. The final dataset contains customer review data for US airlines when flights were canceled. 
Some risks with the data are that it is only for one month, so any predictions would have to be for the following year, in the same month as weather conditions are seasonal. More data would have to be collected to further prove this concept. 
The source data will be stored in an S3 bucket and will get there by way of SQL extraction of the necessary tables, and loading the comma-delimited files for weather and customer service.


