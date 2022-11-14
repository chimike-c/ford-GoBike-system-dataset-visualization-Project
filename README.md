# (Ford GoBike system dataset exploration)
## by (Divine)


## Dataset


### Ford GoBike System Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

There are 183412 individual ride logs in the dataset with 16 recorded data variables per ride log (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Most variables are numeric in nature, however the variables start_time, end_time, member_birth_year are of the datetime datatype and member_gender is a category datatype. 

In the project we carry out univariate, bivariate and multivariate exploratory analysis on the varibales in the GoBike dataset. In this section we use the "Question-Visualization-Observations" framework for explorative analysis of various variables in the dataset. 



## Summary of Findings


After carrying out univariate, bivariate and multivariate exploratory analysis on the varibales in the GoBike dataset, the following findings have been tentaively inferred;

- Users like the service and could make use of it for relatively long journeys. i.e duration_sec goes up to 85444 secs
- The large number of bike stations (start and end) make it easy for users to start and end bike rides anywhere they want. i.e the wide spread for counts on start and end station IDs.
- Wide range of users in sex and age demogrphics (with alot more male users than female/other users). Also age range of users is quite wide with users ranging from 21 to almost 64 years.
- Most of the users of the GoBike service are subscribers, also with relatively much less 20000 users being 'one-time customers'.
- Above 120000 users are male also with about 40000 female users and less than 5000 users identify with other sex categories.
- Most users do not use the bike share for trips/rides.
- A relatively larger proportion of the subscriber users do not use bike share for all trips. However, all the customers (not subscribers) do not use the bike share for all. This could also mean that the feature is not available to customers , only subscribers.


## Key Insights for Presentation


Of the various tentative findings, the following include the relatively concrete insights drwan from analysis;

-  The bike share for all feature is not available to 'one-time'  customers, only to subscribers. This feature can be optimized and can be leveraged to sell subscription to customers. 

-  The wide spread of user demogarphic (sex and age) should allow the company venture into more sub-services for the various demographics e.g. bike buddy(ride with a friend), or keep fit challenges between friends, etc. 










