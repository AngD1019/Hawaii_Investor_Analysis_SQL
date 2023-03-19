# Hawaii Weather Analysis for Investors

## Overview of Analysis  

The purpose of this analysis is to analyze weather data for the island of Oahu, Hawaii, so that an investor in a surf and shake shop can have weather data to inform their investment decision. Since this business's success would be impacted by the weather, the investor requested analysis of weather data for this area, to help them attempt to predict the success of this business venture. This project focused on analyzing the temperature trends in Oahu for June and December, to see if the shop will be successful and a sustainable business year-round. I used Python, Pandas functions and methods, SQLite, SQLAlchemy and Flask to complete the below deliverables.

* Deliverable 1: Determine the Summary Temperature Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

<img width="152" alt="JuneTemps" src="https://user-images.githubusercontent.com/114960958/226148626-79b1f639-b878-4309-a523-769139f550a4.png">

* Deliverable 2: Determine the Summary Temperature Statistics for December
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

<img width="174" alt="DecTemps" src="https://user-images.githubusercontent.com/114960958/226148627-1fafed6f-b7bd-40cb-8fed-79eb49d523a0.png">

* Deliverable 3: A written report for the statistical analysis 
See below report describing the key differences in weather between June and December and summary including two recommendations for further analysis.

## Results
Three key differences in weather between June and December temperature data are noted below:
* June's maximum temperature is 85 degrees, while December's is 83 degrees.
* June's minimum temperature is 64 degrees, while December's is 56 degrees.
* June's mean temperature is 74 degrees, while December's is 71 degrees. 

## Summary

According to the data analyzed in this challenge, there is a relatively small difference (3 degrees) between June's and December's average temperatures in Oahu, Hawaii. This suggests that there is little variability in the temperature throughout the year in this part of the world, which will provide consistency for a business that relies on warm weather. The 70s seems to be warm enough for people to surf, and the maximum temperatures for June and December are also very close, with only 2 degrees of difference between 85 and 83 degrees. The larger disparity is with the minimum temperatures, which are 8 degrees apart with 64 being June's minimum and 56 being December's minimum, however these days are not as common according to this dataset. 

An additional query that I recommend conducting to provide further insight into data to inform investment decisions for this surf shop would be to query precipitation data for both June and December in Oahu. This data analysis was partly completed in the modules preceding this challenge, but I would think that including it with the temperature would give investors and the business owner further insights into what kind of business outcomes they can expect since precipitation impacts whether or not people surf. Another query pertaining to weather that I think would be useful, would be to query storm data related to this area, to see what time of year storms happen on average and how often they happen, as this can impact business beyond just one day of rain, where it can keep people from visiting the island completely. This also makes me think that retrieving some data pertaining to when tourists visit the island would also be helpful to understand what kind of tourist traffic is expected at different times of year. 
