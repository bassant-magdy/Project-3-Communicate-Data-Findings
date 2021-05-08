# Ford Gobike Data Exploration
## by Bassant Magdy


## Dataset overview


> **Data wrangling:**


> * fix multiple fields that are not in the correct dtype.
> * add new columns for trip duration in minute, trip start hour of the day, day of week.
> * add a new column calculating users' age from 'member_birth_year'
> * filter out outlier ages from visual examination of the member age distribution.



## Summary of Findings

> The number of trips peaked around 8-9 AM and 17-18 PM during a day, there were more trips on work days (Mon to Fri) compared to weekends. The riding trips tend to be shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the bike sharing system on normal work days, while more customer flexible use on weekends.

>  Most members were around 20 to 40 years old, male users tend to have shorter trips compared to female and others users, Users who rented the bikes Monday through Friday are slightly older than those who ride on weekends, which supplements the work transport usage that was observed from some of the univariable exploration plots.

> There are a lot more subscriber usage than customers overall. The riding habit/pattern varies a lot between subscribers and customers. Subscribers use the bike sharing system for work transport thus most trips were on work days (Mon-Fri) and especially during rush hours (when going to work in the morning and getting off work in the afternoon), while customers tend to ride for fun in the afternoon or early evenings over weekends. Subscriber usage peaks out on typical rush hours when people go to work in the morning and getting off work in the afternoon.


## Key Insights for Presentation

> Different usage pattern between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days i.e. Monday to Friday whereas customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9 AM and 17-18 PM on work days for subscribers, yet customers tend to use more in the late afternoon around 17 PM Monday to Friday. The short period of usage for subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is mainly for work transport. The pattern of customer use shows that they're taking advantage of the bike sharing system quite differently from the subscribers, heavily over weekends and in the afternoon.