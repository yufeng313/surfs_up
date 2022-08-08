# surfs_up
Surf's Up with Advanced Data Storage and Retrieval
## Overview
In order to invest the surf and ice cream shop business in Oahu, we need to run some analytics on the weather dataset from very island where we’d like to open our shop. Specifically in this challenge, we want temperature data for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round in Oahu.
![hawaii](https://user-images.githubusercontent.com/107179765/183343929-b2ffb186-5ed7-4238-9e81-232f991106c9.png)

## Resources
Data source: hawaii.sqlite <br/>
Software: Python 3.7.6,   Jupyter Notebook 6.4.8,   VS Code 1.68.1

## Results
Filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December, then generate the summary statistics for both two months.<br/>
![june query](https://user-images.githubusercontent.com/107179765/183386738-80b56e4d-97d9-4c41-9527-cdffb7f8dd4c.png)
![december query](https://user-images.githubusercontent.com/107179765/183386755-6ee40ce5-ff14-4257-aa80-9181b7b95bf8.png)
![june temps](https://user-images.githubusercontent.com/107179765/183343774-14a0157d-16b6-462c-bfd6-f84a93914394.png)
![december temps](https://user-images.githubusercontent.com/107179765/183343808-903be047-85ab-4a35-a8c3-eda74108a4a8.png)<br/>
From the summary statistics we can see that:<br/>
-	June temperatures range from 64~ 85 °F whereas December temperatures range from 56~ 83 °F. The weather in December is a little bit lower than in June but not too much overall.
-	The average temperature in June is 75 °F whereas it’s 71 °F in December, showing a moderate climate all year round.
-	Temperatures in December are more spread out than in June since the standard deviation for December temperatures is higher, which means December has more temperature fluctuation.
-	The number of datapoints in December is less than June, as some of the stations may not that active in December.

## Summary
### Results summary
The summary statistics for both June and December indicates that these two seasons had relatively warm temperatures, with the temperature above 70 °F, 50% of the time in December there starting a business in Oahu seems to be very good option.
### Additional queries
In order to gather more weather data for June and December, I would recommend two additional  queries below:<br/>
1.	Precipitation difference between June and December: to determine which month has more rainy weather, and count the days where there are moderate rain in each month.
2.	The summary statistics of temperatures/precipitation grouped by each station in June and December: to see the higher/lower temperatures and precipitation levels at different locations, which will provide us the best data we want for shop location choosing, as we may interested in the weather station closest to our prospective location.
