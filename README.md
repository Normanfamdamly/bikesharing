# Bikesharing - Module 14 Challenge
---

## Overview of the Project
---

The project was created as a means to convince our investors to invest in a bike sharing program in Des Moines, IA.  This is being completed through the creation of a story in Tableau to create our proposal.  Our analysis consisted of utilizing Jupiter Notebook to convert trip duration to a datatime datatype via Pandas. Then load the CSV file into Tableau to create multiple visualizations such as:

                - Top Starting Locations for CitiBike Rentals
                - Top Ending Locations for CitiBike Rentals
                - Trips by Weekday per Hour
                - Trips by Weekday per Hour by Gender
                - Customer vs. Subscriber by Gender by Weekday
                - Checkout Times by Users by Hour(Minutes of usage)
                - Checkout Times by Users(Gender) by Hour(Minutes of usage) 

### Resources
---

    * Data Source: NYC_CitiBike_Challenge.ipynb, 201908-citibike-tripdata.csv and updated_citibike_201908.csv
    * Data Systems: Jupyter Notebook, CSV, Tableau and CitiBike Website
    
 ## Results
 ---
This can be all reviewed in my story on Tabeau here [Tableau Story](https://courses.bootcampspot.com/courses/1605/assignments/33924?module_item_id=669004)

There is a defined patter to the starting and ending locations for the CitiBikes.  You will see how they are clustered in the city in following two charts.  This shows us that in the denser area of Des Moines where there is a large mix use are full of offices, apartments and restaurants the bike rentals will do very well.
 
![top_starting_locations]( https://github.com/Normanfamdamly/bikesharing/blob/main/images/top_starting_locations.png)
![top_ending_locations](https://github.com/Normanfamdamly/bikesharing/blob/main/images/top_ending_locations.png)
 
As you can see from below, we have a large usage from the 5PM to 7PM time frame for the bikes throughout the week.  There is also a relative constant usage in the 7AM to 9AM to, which lends itself to commuter usage for work.  Then a strong constant usage throughout the day on Saturday. 
![trips_by_weekday_for_each_hour.png](https://github.com/Normanfamdamly/bikesharing/blob/main/images/trips_by_weekday_for_each_hour.png)

The usage is predominately male in the gender breakdown. I find this interesting and would like to study more why that is, as I think it would be helpful in our marketing to know. Especially since our largest user base are our subscribers.
![trips_by_weekday_per_hour_by_gender.png](https://github.com/Normanfamdamly/bikesharing/blob/main/images/trips_by_weekday_per_hour_by_gender.png)
![users_trips_by_gender_by_weekday.png](https://github.com/Normanfamdamly/bikesharing/blob/main/images/users_trips_by_gender_by_weekday.png)
 
 These next two charts show you the number of bikes in use by the hour, then broken down by the number of minutes in use in each hour.  You will see that as the hours of the day go one there are a larger number of bokes being used, but not always for long durations. The second chart continues to reiterate what we saw above, that the male population happens to be our more dominate user and subscriber to the service.
 ![checkout_times_for_uesrs.png](https://github.com/Normanfamdamly/bikesharing/blob/main/images/checkout_times_for_uesrs.png)
 ![checkout_times_by_gender.png](https://github.com/Normanfamdamly/bikesharing/blob/main/images/checkout_times_by_gender.png)
 
 ## Summary
 ---
The data and visualization above point to the direction that this could be successful in Des Moines, IA if, we are able to do the following:
   
    - Place the bike racks in locals that are dominated by mix use real-estate (Businesses, Apartments and Retail)
    - Subscribers are our primary utilizers
    - Trips duration are 15 minutes or less
    
It would be helpful to know why the subscribers or users are utilizing the bikes.  What is their main reason for the transportation.  Also, I think breaking the it down by age may help up better market to the male population and maybe drum up more business from the female population if we know the sweet spot.
