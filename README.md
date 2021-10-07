# bikesharing
Using Tableau to create vizualizations of New York CitiBike Ride Share data.

![](https://github.com/LauraHaq/bikesharing/blob/main/images/citiBike.png)  
###### Ira L. Black- - Corbis via Getty Images

## Overview of the analysis:
This is an analysis of New York City's bike ride share program called CitiBike. A similar program is propsed in Des Moines, Iowa and this project is to provide visual data of the success of CitiBike in New York City for a possible investor. The data was collected, transformed and an extract of the data was used in Tableau Public to provide a shareable user-friendly dashboard to read the CitiBike data gathered from 2019. 

#### Data
 - [CitiBike Data](https://www.citibikenyc.com/system-data)

#### Tools
 - Jupyter Notebook
 - Tableau Public

## Results
### Completed Dashboard
- [link to dashboard](https://public.tableau.com/app/profile/laura.haq/viz/CitiBikeChallenge_16331478001120/CitiBikeNYCAnalysis?publish=yes)

### Using Jupyter Notebook
- Tripduration data type changed to datetime:

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/convert_datetime.png)

- Transformed dataframe exported into a new file witout index:

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/output_part2.png)

### Using Tableau Public
![here](https://github.com/LauraHaq/bikesharing/blob/main/images/tripdurations.png)  
Line graph of all users' duration with an hour filter. Relevant data is in hour "0" because all trip durations were listed under 1 hour to get needed data. Line graph peaks at a bike ride of 5 minutes. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/tripdurations_gender.png)  
MultiLine graph of each gender of duration with gender and hour filters. Also filtered down to hour "0" to show rides lest than an hour long. Male and Female spike at five minute care rides. Unknown gender types show no peaks in the data but that it rises at five minutes then drops at 30 minute. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/trips_by_weekday.png)  
Heatmap of bike trips by hour for each day of the week. The maps shows very high usage at 8:00 am and 5-6:00pm Monday through Friday. Saturtday and Sundays show there is an increase at 9:00am the bikes stay steady in use until drops off at 8pm. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/tripts_by_gender.png)  
Heatmap shows number of trips by gender for each hour of each day of the week with gender filter. Shows a strong heat reading with high number of rides for "MALES" versus "FEMALES" or "UNKNOWN". For those who reported a gender showed the same pattern as previous heat map with highest usage during commuting hours of 8am and 5pm while "UNKOWN" shows a strong usage during the visiting hours to New York City on the weekends.

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/usertrips__gender_weekday.png)  
Heatmap shows number of trips for each usertype and gender for each day with user and gender filters. When filtering to "Customer" we learn that the peaks are now on the weekends. Also those who did not report thier gender had more usage on the weekends while both "MALES" and "FEMALES" showed highest uses during commute hours on the weekdays overall. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/Aug_peakHours.png)  
Bar graph shows peak hours of August. Clearly shows the spikes of use during commute hours. Also, there is a bar on each hour of the day. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/End_locations.png)  
Map using geophraphical data to map ending locations of bike trips filter by birth year. Bikes are being utilized to access all areas of New York City for all areas of interest.

## Summary
All visusalizations show that in terms of people taking part of the bike share program that CitiBike Ride Share is a success in New York City. This is due to that with only 13,983 BikeIDs in a Text box in Tableau with "Count(Dintinct)" selected there were 2,344,244 total rides reported in 2019. The reason why 13,983 bikes could provide this many rides is due to what is seen in the line chart of the bikes being used for only minutes for each duration of trip regardless of gender. The User Trips by Gender per Weekday initially protrays that Male Subscribers overpowering the heatmap. In order to see what is happening in other demographics the dashboard allows user to filter out to each box seperately. Looking at Usertypes, the "Subsribers" continues to portray highest usage during the weekdays. Meaning these are local New Yorkers who are regular customers as they are communting to work or school. So even though Des Moines is not a world travel destination like NYC, it would be mainly used by local residents of city. Between the quick five minute commutes and the majority of these trips are during work hours I would like to look into comparing the density and avg commutes between the two cities. No matter the age all areas of New York and some outter areas are benefiting from the program. Also, all hours of the day have reported usage. This shows that all ages, all times of the day, and all areas of New York City are benefitting from CitiBike Ride Share program. I would like to gather data of Des Moines Night life to help esitmate the hours of usage and also the distance between public transportation stations to understand how much area is to be covered with program and number of bikes needed. Overall, Des Moines would benefit from a ride share program however will need to collect data to know the humber of bikes and coverage area.
