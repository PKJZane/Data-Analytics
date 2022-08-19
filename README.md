# Ford GoBike System Feb 2019 Data Exploration
## by Michael Appiagyei


## Dataset

> The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco bay area for the period of February, 2019. The dataset contains 183412 records with 16 features. I did some preliminary data wrangling to tidy up the data. I also generated some features that were used in the analysis. The data cleaning include the following:
- Remove missing values
- Fixing incorrect data types for some variables
- Removing columns that are not of interest
- Removing some outliers from the data set for further analysis

The Features I generated included the following:
- Age of riders computed from their year of birth
- Day of the week
- Time of day
- Duration of trips in minutes


## Summary of Findings

> It was observed that the average trip distance was ~12 minutes. The trip distance depended on the age of the rider; with younger riders recording higher average distances, whether it is a weekday or weekend; with more trips done on weekdays but higher trip distances covered on weekends. Riders aged 35-38 recorded the most trips. Female riders had a lower mean age compared to their colleagues, it was observed that the female gender had a high average trip distance as well. 


## Key Insights for Presentation

> Age and Gender seem  the likely predictor of trip durations. Subscribers tend to record more trips but those trips are of shorter distances compared to customers. This may indicate normal commuting as opposed to customers who mainly used it for leisure and recorded high mean distances. There were also more trips done on weekdays than on weekends, however the average distance covered on weekends were higher than that of weekdays. This again indicates that on weekdays, riders use the bikes for short distances perhaps commutting to work and other places of business whereas on weekends, it is mainly used for leisure and other fun rides.  