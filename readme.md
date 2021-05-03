# Project - Ford Go Bike 2019 Data Exploration
## by (Ibrahim Sayed Ahmed)


## Dataset

Bay Wheels (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.

### Data wrangling process:

- fix multiple fields that are not in the correct dtype, i.e. start_time, end_time should be datetime type, Change data type to int for columns ('start_station_id' , 'end_station_id' and 'member_birth_year')and ('user_type' and 'bike_id') can be changed into a categorical data type., etc
- add new columns and Extracting time information form the 'start_time' and 'end_time' columns. We can derive information about the specific months, weekdays, hours from this aggregated data.
- add a new column calculating riders' age from 'member_birth_year'


## Summary of Findings

- The most popular times for riding a bike is usually from 8:00-9:00 am and 5:00-6:00 pm. 
- bSubscribers use the bike sharing system for work commnute thus most trips were on work days and when going to work in morning and getting off work.
- The Customers users (casual users) usually took more time in their rides than Subscribers.
- Most riders were male subscribers who did not use bike share for all trips. Most members were around 25 to 40 years old, as the age gets older, bike usage dropped significantly. 


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
- Different usage pattern/habit between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends, especially in the afternoon. 
- A high percentage of customers and subscribers use bikes for travel during the rush hours.
