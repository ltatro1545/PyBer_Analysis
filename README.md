# PyBer Analysis Using Matplotlib
## Overview and Purpose
PyBer, likely Uber's make-believe competitor, gathered data on trips from drivers across 120 different cities within the United States. This data came from two separate csv files. The information gathered included:
  - Date and time of individual rides
  - Ride identification number
  - City name
  - City type (Urban, Suburban, or Rural)
  - Driver count for each city

The two csv files were merged and subsequently analyzed using Pandas to compare fares between drivers of the three city types.

## Results
![ChallengeSummary](https://user-images.githubusercontent.com/92493572/142776337-6997d61d-8c02-4ed9-9095-092fea9449c9.png)

As expected, rural areas had the lowest amount of rides and drivers, urban areas had the highest number, and suburban areas were inbetween the two. The notable difference is how much the average fares differ. Rural areas average $34.62 per ride, whereas urban drivers average $24.53 per ride. To summarize the rural data, rural drivers earn:
  - 41.13% more per ride than urban areas
  - 11.79% more per ride than suburban areas
  - 234.89% more than urban drivers
  - 40.48% more than suburban drivers

Rides per driver are as follows:
 - Rural: 1.60
 - Suburban: 1.28
 - Urban: 0.68

Rural drivers had 135.29% more rides per driver than urban drivers, and 25% more than suburban.

A comparison of total fares by city type was also charted for visual aid.
![ChallengeChart](https://user-images.githubusercontent.com/92493572/142786129-34777da3-57b7-4aa4-8006-be0f394ffaf1.png)

As urban cities have more drivers, a higher total fare was expected, especially compared to rural areas.

## Summary
The data, although intriguing, lacks critical pieces of information to ultimately be utilized. At this time, PyBer should put emphasis on acquiring information such as the distance traveled per trip, duration of each trip, and average wait times between trips.

The above results would imply that there are simply far too many urban drivers than there is needed to meet ride demands. With urban areas only having 0.68 trips per driver, it may be worthwhile to incentivize drivers to go elsewhere or target specific high demand times, if any.

The major disparity could also be in part due to time stuck in traffic, which could be addressed by restructuring the pricing calculations. If, for instance, distance traveled was causing rural areas to earn significantly higher amounts than urban drivers (who may often be held up in rush hour traffic), this could be rebalanced internally by putting more salary emphasis on time spent in the vehicle versus miles traveled.

The initial anaylsis has provided points of interest to investigate, though it is strongly recommended to father additional information before making any sizeable decisions. Perhaps one alternative to purchasing or downloading route information, a survey could be sent out to the drivers and riders using the PyBer app referencing the above topics to gain potential insight to the problem.
