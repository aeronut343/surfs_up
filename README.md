# surfs_up
## Background and Purpose
This analysis follows a fictional business venture where a man is trying to establish a surf and icecream shop on the Hawaiian Island of Oahu. He has managed to get the support of an investor, but contingent upon an analysis of the weather trends from the last several years.

## Analysis
### Resources
The investor provided a SQLite file with raw weather readings from multiple weather stations around the island. SQLAlchemy was used to extract the data, and the clean-up and analysis was done primarily with Pandas.

### Results
The temperature in Oahu is remarkably stable, with a mean of 73.1 degrees (F) and a standard deviation of only 4.7. This is further proved by the interquartile range which is only 7 degrees. The precipitation comes in intense spurts consistently throughout the year, which means it is highly unlikely that the business would be negatively affected by a prolonged period of precipitation.

The following is a list of some key differences in temperature between the summer and winter months (June vs December)
- Mean: June has a mean temperature of 75 degrees, while December is slightly colder with a mean of 71
- Std Dev: June has slightly less deviation from the mean at 3.3 degrees, compared to Decembers 3.7
- Min/Max: June and December have similar maxes at 85 and 83, respectively. June has a much higher minimum temperature than December at 64 and 56 respectively.

### Conclusion
The analysis shows that a surf and icecream shop would likely not be negatively impacted by the temperatures year-round in Oahu. Further analysis should be done on the precipitation and when it is likely to rain in relation to when it is likely to be cold.


