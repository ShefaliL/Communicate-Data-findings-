# #Exploratory Data Analysis - Ford Gobike
## by Shefali Luley


## Dataset

The dataset originates from Ford GoBike is the Bay Area’s bike share system. Bay Area Bike Share was introduced in 2013.It services San Francisco, the East Bay and San Jose.
Similar to other bike share systems, Ford GoBike consists of a fleet of bikes that can be unlocked in one station and returned in any other network station.
Thus, this is ideal for one-way trips.These bikes are available for use thorughout the year and riders have access to all bikes in the network.

Following are the 16 columns in the data set used for assessing, cleaning and visualization:
				
Trip Duration (duration_sec)
Start Time(start_time)
End Time (end_time)
Start Station ID(start_station_id)
Start Station Name(start_station_name)
Start Station latitude(start_station_latitude)
Start Station longitude(start_station_longitude)
End Station ID(end_station_id)
End Station Name(end_station_name)
End Station Latitude(end_station_latitude)
End Station Longitude(end_station_longitude)
Bike ID(bike_id)
User Type(user_type)
Birth Year of the Member(member_birth_year)
Gender of the Member(member_gender)	
Bike Share of All the trips(bike_share_for_all_trip)

To download the csv data files: https://www.fordgobike.com/system-data


Key Insights
The data set consists of 16 columns out of which few have null values present in them. 
Intially , we analyse the data set and delete or select few columns which are needed for our investigation. The data set can be further modified as per the user.
The key insights for my data analysis include : Assessing the data set and then cleaning it.
Secondly, With the help of Univariate, Bivariate and Multivariate exploration and removing the outliers I was able to know the countof which gender is higher for renting the bike and on which days.
Furthermore, I was also able to assess which age group travels/rents more, which user type rents more often and much more

Data Consistency
The data have two types of User type "Customer" and "Subsciber".
It also have the start and the end time of the journey, station id and station name as well as the latitude and longitude of starting as well as the ending points.
The data set is little inconsistent since they have null values present in few columns which are further dropped. The data set is cleaned from proper visualization with zero null values.

Summary of Findings

The number of males renting a bike is the highest and the number of females renting a bike is less than 50% than the number of males.
The number of people renting on weekdays is significantly higher than the one's renting on the weekends.
The number of subscribers of the bikes are quite high as compared to the customers.
Males travel less distance on an average as compared to female/others.
Average distance travelled by people of age group 30-40 is higher than that of 20-30 for all the three cases.


