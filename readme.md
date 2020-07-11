# Ford GoBike DataSet Visualization
## by Chaitanya Bachhav


## Dataset

> The data set consists bike share data for 519700 bike rides. Each bike ride (row) has 13 features (columns) which include user-type, trip start station, end station, start time, end time and bike_id.Ford GoBike is a bike share system functioning in United States, this data set consists information about bike rides made using Ford GoBike in the year 2017.The objective is to perform explanatory analysis on this data-set and provide necessary visuals. 

## Summary of Findings

>-On a linear scale the distribution of duration time was right skewed and had a long tail, this warranted the use of a logarithmin scale. On the logarithmic scale the distribution appears to be uni-modal. The peak was observed at around 600 seconds. 
 - It appears the most of the trips have ocurred between July 2017 and December 2017. There is very less trip data from June 2017.
 - The start and end trip data are comparable, i.e. number of trips started  = number of trips ended. Few trips have started on  31 Dec 2017 and ended on 1 Jan 2018, which explains the presence of 2018-01 in the plot. Maximum number of trips have occured in October 2017. 
 - The plots show that the most bike rides occur on week days, this suggests that users use bike to go to work.
 - It was  observed that the mean duration of casual customers is around 2550, and that of subscribers is around 700, this suggests that casual customers ride longer than subscribers. This is interesting because the number of trips made by subscribers is more than number of trips made by customers. 
 - It was observed that casual cutomers go on longer bike rides than regular subscribers. The month vs mean trip duration plot depicted that the mean trip duration was highest in July 2017 and declined after that. Longest trips occurred on week ends especially Sunday.
 - It can be observed that in every month most of the bike rides occur during working days (week days) and the number of bike rides is lesser during weekends.

## Key Insights for Presentation

> Changed the axis tick labels for months so that they show month names instead of numbers. I also added descriptive tick labels for axes. The user-type vs Duration includes annotations that give the mean duration. 