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
