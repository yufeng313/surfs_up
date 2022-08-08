# surfs_up
Surf's Up with Advanced Data Storage and Retrieval
## Overview
In order to invest the surf and ice cream shop business in Oahu, we need to run some analytics on the weather dataset from very island where we’d like to open our shop. Specifically, we want temperature data for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round in Oahu.
![hawaii](https://user-images.githubusercontent.com/107179765/183343929-b2ffb186-5ed7-4238-9e81-232f991106c9.png)

## Resources
Data source: hawaii.sqlite <br/>
Software: Python 3.7.6,   Jupyter Notebook 6.4.8,   VS Code 1.68.1

## Results
Filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December, then generate the summary statistics for both two months.<br/>
![june temps](https://user-images.githubusercontent.com/107179765/183343774-14a0157d-16b6-462c-bfd6-f84a93914394.png)
![december temps](https://user-images.githubusercontent.com/107179765/183343808-903be047-85ab-4a35-a8c3-eda74108a4a8.png)<br/>
From the summary statistics we can see that:
-	June temperatures range from 64~ 85 °F whereas December temperatures range from 56~ 83 °F.
-	The average temperature in June is 75 °F whereas the average temperature in December is 71 °F, showing a moderate temperature and very little fluctuation between the two periods from an average standpoint.
-	Temperature in December are more spread out than in June since the standard deviation for December temperatures is higher.

## Summary
Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
