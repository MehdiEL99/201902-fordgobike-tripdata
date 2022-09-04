# 201902-fordgobike-tripdata
Analyse data of 201902-fordgobike-tripdata

Dataset :   2019-fordgobike

The dataset, 2019-fordgobike-tripdata.csv, is downloaded from Ford GoBike and licensed by Ford GoBike. 
This dataset includes 183411 trips with 16 features such as locations, time, and user attributes. 
There are start and end stations. I used thoses columns to create Distance column,
and trying to understand the behaviour of members how much they need of time to go from one station to other
is age and gender od user_type has an effect on duration and distance
I created 3 new columns 'duartion_min, duartion_hour, speed' those columns is gonna help me to understand the behaviour of members 
I removed outliers from distance , age , duration cause all those column has a high skew distrubition 


Summary of Findings :

Univariate exploration: the number of trips gradually decreases when the weather becomes colder. 
During the day, there are more trips in the morning and afternoon than the night.
 Also, there are more trips during the weekdays and less trips during the weekends. 
It makes sense that there are more subscribers than customers pricing. For the gender groups, 
the number of trips in male riders is 3 times more than the number of trips in females. It needs to be investigated more. 
Distance and duration are not a normal distribution that why i used The Empirical rules to remove outliers

Bivariate exploration: 

there is a low correlation between age and duration of trips and distance also. 
In each month, besides July (the program just launched), from August to October, the number of trips gradually increases and it decreases in the winder (November and December). 
Biking is definitely correlated with the weather. 
After removing outliers from distance and durationi got a high correlation between them 
we have more data about subscriber people in Male and female gender is prove that subscriber do so much riding than customer

Multivariate exploration: 

Male use more distance with less duration it proves that they use more speed in trips ,and that is exist in every age of members 
subscribers also use more speed in every week days and period days combaring to Customers
i chose the age between 29 and 32 cause there is so much data and i plotted Distance ,duration_hour ,age ,gender ,period day and weekday
to see the diffrence between gender , Time and user type in controlling ditance and duration.
   
Key Insights for Presentation
After Analysing data we will say that Age has no effect of Distance and duration of tips between station
Gender has an absolute effect on duration and distance Male tends to be use more speed than Female
Subscriber use more speed than Customer
weekdays as sunday and saturday has less trips cause sunday and saturday is a weekend so may be there is no job to go for
members do more trips in morning and afternoon than nights
