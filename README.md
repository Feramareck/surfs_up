# Surfs_up

## Overview of the analysis:
This analysis aims to investigate Oahu's temperature data for the months of June and December in order to determine whether the surf and ice cream business is sustainable year-round.

## Results:
- We used the hawaii.sqlite file as a base, which contains the station measurements database. This file contains the measurement table which contains information about the measurement stations, date, precipitation and temperature.
- For the months of June, considering all the years of the database, we have a sample of 1700 measurements, an average temperature of 74.9F, being the minimum 64F and the maximum of 85F and 50% of the sample with temperatures above 75F, as we can see in the image below containing the summary statistics.  
![Temp_Jun](https://user-images.githubusercontent.com/111664141/197874739-11336412-4cb5-45d9-bac6-d01426c1cc40.png)

- For the months of December, considering all the years of the database, we have a sample of 1517 measurements, an average temperature of 71F, being the minimum recorded of 56F and the maximum of 83F and 50% of the sample with temperatures above 71F, as we can see in the image below containing the summary statistics.  
![Temp_Dec](https://user-images.githubusercontent.com/111664141/197874804-3cb73dec-8e47-4abd-a594-7a9610992a7c.png)


## Summary:
Analyzing the months of June and December, we see that both have adequate average temperatures (June - 74F and Dec - 71F) both for surfing and for selling ice cream throughout the year that make the business suitable.  
An analysis that would be interesting to carry out would be to analyze the precipitation to verify the levels of rain, which can also interfere with the sales of the business.  
Another analysis would be to check the descriptive statistics by measurement stations to see if they show any discrepancy between those that are more active and those that are less active.  

All queries generated for this analysis are detailed and commented in the SurfsUp_Challenge.ipynb file, as well as the hawaii.sqlite database.
