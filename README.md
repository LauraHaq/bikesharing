# bikesharing
Using Tableau

## Overview of the analysis:
This is analysis of New York City's CitiBike for 2019 to help visualize its data to receive funding for a similar bike ride share program for Des Moines, Iowa. Data will need to be collected, transformed and pull and extract of the data into Tableau Public. The goal is create a Story using visualizations of the extract data to save in Tableau Public to be shareable to possible funding partners.

#### Data
 - [CitiBike Data](https://www.citibikenyc.com/system-data)

#### Tools
 - Jupyter Notebook
 - Tableau

## Results
#### Using Jupyter Notebook
- Tripduration data type changed to datetime:

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/convert_datetime.png)

- Transformed dataframe exported into a new file witout index:

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/output_part2.png)

#### Using Tableau Public
![here](https://github.com/LauraHaq/bikesharing/blob/main/images/tripdurations.png)
Line graph of all users' duration with an hour filter. Relevant data is in hour "0" because all trip durations were listed under 1 hour to get needed data. Line graph peaks at a bike ride of 5 minutes. 

![here](https://github.com/LauraHaq/bikesharing/blob/main/images/tripdurations_gender.png)
MultiLine graph of each gender of duration with gender and hour filters. Also filtered down to hour "0" to show rides lest than an hour long. Male and Female spike at five minute care rides. Unknown gender types show no peaks in thee data but that it rises at five minutes then drops at 30 minute. 

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

