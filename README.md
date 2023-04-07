# (A DATA VISUALIZATION FOR FORDGOBIKE DATA)
## by (JOE SOLOMON OBUSOR)


## Dataset

 This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
 The dataset was downloaded and loaded to the jupyter notebook.
 A comprehensive data wrangling was performed on the dataset in the following aspect:
 
### 1. ASSESSING THE DATA
 > The loaded data was assessed both visually and programmatically. The data was then further assessed for quality and tidiness issues
 
#### QUALITY ISSUES
1. Start_time and End_time should be of datetime datatype
2. The duration in seconds may not give a good estimation of the trips duration.
3. The member_gender column should be a categorical datatype instead of object.
4. There is no day coclumn
5. The user_type column should also be a categorical datatype
6. The dataset contained missing/null values
7. Some of the cfeatures are not important, should be dropped
8. There is no age column
 
### 2. CLEANING THE DATA
- The start and end time datatypes were converted to datetime
- Duration in hours column was created and duration in seconds column dropped.
- Member_gender, user_type and bike_share_for_all_trip columns were converted to categorical datatype
- Start day and end day columns were created
- The less important features were dropped
- Member_age column was created
- Missing values were dropped as they constituted less than 5% of the dataset.

### 3. STORING THE DATA
> The cleaned dataset was saved and stored as 'fordbike_clean.csv'

 
 

## Summary of Findings

1. The male gender dominated the rides/trips
2. Subscribers were more involoved in the rides than the customers
3. The longest trip duration by the male was about 40 mins more than the female trip.
4. Thursday had more trips than evey other day.
5. The age of the riders were well distributed across the users
6. Customers are more active and involoved in the rides during the weekends than subscribers.
7. The age range with the most participation is withine 20 - 40 years.


## Key Insights for Presentation
- The male gender dominated the rides/trips
- Subscribers were more involoved in the rides than the customers
- Most of the trips were on Thursday
- Customers participated more during weekends