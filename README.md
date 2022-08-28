# Ford GoBike Ride Sharing System
## by Ezemonye Ordu Omereji

## Dataset

> This project dataset contains exploratory analysis of the Ford GoBike Ride Sharing dataset which includes data related to individual rides made in February, 2019 covering the greater San Francisco Bay area. The data set comprises of 183,412 records of bike trips, with a total of 16 features (duration_sec, start_time, end_time, start_station_id,start_station_name, start_station_latitude,start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type,member_birth_year, member_gender, bike_share_for_all_trip). This data set was provided by [Udacity]('https://video.udacity-data.com/topher/2019/April/5ca78b26_dataset-project-communicate-data-findings/dataset-project-communicate-data-findings.pdf')


## Data Wrangling
>  start_time and end_time were object types and converted to datetime type as expected.
>  start_station_id, end_station_id were float types and converted to string type as expected
>  bike_id was integer type but did not require any calculations and was converted to sString type as expected 
>  user_type and member_gender are object types and converted to category for easire analysis
>  trip duration is in seconds, new column derived in minutes
>  start_station_latitude, start_station_longitude, end_station_latitude and end_station_longitude appear to be     irrelevant to the analysis and were dropped.
>  member age was derived from member birth year 

## Summary of Findings

 Findings indicated that at rush hours of 8:00hrs and 17:00hrs most week days(mondays - fridays) witnessed the peak in usage of the bike system (Mon-Fri) compared to weekends. While there were frequent rides during the week days, the duration of the rides were shorter than that of the weekends which saw longer ride durations. Apparently, the usage within work days were specific while the weekends appear relaxed and casual. The shorter riders showed to be more of males, while females and other genders appeared to have longer rider durations.

 The active age range for more frequent users of the bike system was between 20 and 40 years of age and as users age increased, rides dropped accordingly.  

 In all, Subscribers were seen to be patronizing the system more than customers.

 
## Key Insights for Presentation
 There were two types of ride users for this data set. Subscribers were very frequent with bike rides within week days whereas customers used the system more on weekends. 
