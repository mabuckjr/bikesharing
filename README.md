# CitiBike in Des Moines Analysis
## Overview
The purpose of this analysis was to look over the data for a month of citibike rides in New York City to get an idea of what to expect if the bikes were deployed in Des Moines. While Des Moines is a very different city than NYC, we can expect many of the same trends to carry over to the new location. The data was supplied in the form of a .csv, which contained detailed information about each ride that month (i.e., trip duration, start time, end time, various bits of information about the user, location, etc.). We then uploaded the data into Tableau, where it could be sorted through very easily since the data was already "clean." The different worksheets were eventually combined into a Tableau Story that could be presented to stakeholders who would be interested in adding citibikes in the new location.
## Results
[Link to the interactive Tableau Story](https://public.tableau.com/app/profile/andy.buck8221/viz/citibike_workbook/CitibikeinDesMoines?publish=yes)
### Citibike User Breakdown
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/customer_type.PNG)
#### Most of our users at in NYC are Subscribers. Des Moines should expect a similar proportion of users if marketed in a similar manner.
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/customer_type_gender.PNG)
#### Our users also tend to identify as "Male," so the primary target audience would be men. As you will see in the charts below, most of the rides start around 8-9am and 4-5pm, suggesting that male commuters make up the majority of our userbace in NYC.
### Trip Activity
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/stoptime.PNG)
#### Trip activity is higher on weekdays around the start and end of the work day.
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/number_to_string_stoptime.PNG)
#### When broken down by gender, we see that this is most true for males, but isn't necessarily the case for females and our unknown category.
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/stoptime_gender_weekday.PNG)
#### This graph tells us two things: that most of our "unknown" genders are not subscribers (hence why we don't have that data from them), and that males tend to use the bikes most heavily on Mondays, Tuesdays, Thursdays and Fridays. 
### Trip Duration
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/trip_duration.PNG)
#### Trips tend to be short, most of them being 20 minutes or less.
![](https://github.com/mabuckjr/bikesharing/blob/main/Resources/trip_duration_gender.PNG)
#### Gender doesn't seem to be much of a factor in trip duration, as the peaks for males and females follows a similar pattern. The unknown category may not use the bikes for commuting as much from the looks of this trend.
## Summary
The results show clear trends: working males are the dominant target audience, and the times the bikes are most used are during weekdays during the usual morning and afternoon commutes. Des Moines is a very different city in NYC, but there's a good chance that this trend would carry over. While tourists would likely use these bikes on weekends, it's not likely they would make up a large percentage of riders in Des Moines (especially since it isn't considered as much of a tourist destination as NYC). The fact that women aren't using the bikes as much as men means that there's a chance for Des Moines to capitalize on a market that NYC hasn't been able to attract. Perhaps the marketing team can do some research on how to best attract different usertypes once it the bikes are deployed. 

I would suggest that an analysis is done to find the relationship between birth year and trip duration, as well as trip frequency. This will help us better understand how different age groups tend to use citibike. These charts would best be displayed as bar charts, perhaps with a filter for gender as well.

Another chart that could be helpful would be to find the average distance travelled per trip, as well as the average total mileage completed for the month. This could be displayed in a variety of ways, comparing it to age, gender, or even usertype. This would help us get a better idea of how many miles our bikes travel in a given month.
