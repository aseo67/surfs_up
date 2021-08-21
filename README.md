# Surfs_Up Analysis
Module 9 Challenge Analysis File Links
- ![SurfsUp_Challenge.ipynb](https://github.com/aseo67/surfs_up/blob/main/SurfsUp_Challenge.ipynb)
- ![hawaii.sqlite](https://github.com/aseo67/surfs_up/blob/main/hawaii.sqlite)

## Overview of Analysis
In preparation for starting a Surf n' Shake shop in Hawaii, which will serve ice cream and surf board services for local customers and tourists, this analysis explores weather patterns to ensure that the island of Oahu is the optimal location to open shop. Various weather metrics are explored to determine if this business will be sustainable year-round, specifically looking into data in the months of June and December. 

## Results
3 major points/differences in weather between June/Dec from 2 analysis deliverables (using images as support)

![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_June%20Temps%20Stats.png)
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_Dec%20Temps%20Stats.png) 

1. The average temperatures in Oahu between the months of June and December are very similar - 75°F in June vs. 71°F in December. This is promising and shows that the average temperature doesn't deviate much, whether in the middle of the summer or in the middle of the winter, which is ideal for year-round sustainability. 
2. Furthermore, the max temperature is very similar between these two months as well - 85°F in June vs. 83°F in December. The temperature in December seems to reach similar highs as in the middle of summer, again enforcing the hypothesis that weather will be ideal even in the winter time. 
3. Finally, a notable difference in temperatures between the two months are the minimum temperatures. In June, the minimum temperature is 64°F, whereas in December it is 56°F. This suggests that the temperature lows get chillier in the winter time, so bigger swings in temperature may be expected. 

## Summary
### Summary of Results
Overall, the temperature analysis so far seems to indicate that weather will be favorable for an ice cream/surf shop, even in the winter time. Lower temperature swings may require some strategizing to make use of the shorter warm timeframes of the day in the winter vs. the summer, but the average and maximum temperature data suggests that temperature is still similar to the summer time and feasible for this shop. 

Some additional analysis has also been conducted to explore (1) the precipitation in June vs. December, and (2) analyzing the weather data at a station-level by identifying top stations in these months and the respective top station's weather data. 

### Precipitation
Precipitation data between the two months are similar, with average precipitation amounts of 0.1 in June vs. 0.2 in December. This suggests that rain isn't common in Oahu, regardless of the season. However, when it does rain, the heaviest rainfall does seem to occur in the winter time, as the results show maximum precipitation amounts of 4.4 in June vs. 6.4 in December; thus, heavy rain days may need to be better prepped for in the winter time. 

![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_June%20Precip%20Stats.png)
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_Dec%20Precip%20Stats.png)

### Top Stations' Weather Data
To gain insight into weather data at a station-level, this additional analysis first parses out which stations produced the most weather entries in the months of June and December. Here we see that stations 'USC00519397', 'USC00519281', 'USC00513117' had the most activity in June, whereas in December it was from station 'USC00519281'.
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_June%20Active%20Stations.png)
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_Dec%20Active%20Stations.png)

Focusing on the top station from each month, the minimum, maximum, and average temperatures and precipitation amounts were retrieved. Here we observe that the top station in June does have higher temperatures overall across the board, vs. the top station from December. Similarly, for precipitation, while the average rainfall from the top station in December isn't too far off from the top station in June, the maximum rainfall is significantly more. 
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_June%20Top%20Station%20Stats.png)
![Screenshot](https://github.com/aseo67/surfs_up/blob/main/Screenshot_Dec%20Top%20Station%20Stats.png)
