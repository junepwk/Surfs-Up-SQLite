# Surfs Up with Advance Data Storage and Retrieval

## Overview
This analysis is to provide an insight for an investor to determine the stability of opening an ice cream and surf shop in Oahu, Hawaii. The weather was stored in a SQLite database for a quick set-up without requiring a server. With the weather data provided the precipitation, temperatures and number of stations were all analyzed to help future investors get a deeper understanding on whether their investments would be worthwhile.  In addition, temperature data for the months of June and December in Oahu were extracted from the date column in the weather data for further analysis to determine if the surf and ice cream shop business was sustainable year round.

## Resources
- Software: Jupyter Notebook 6.3.0, Python 3.7.10
- Database: SQLAlchemy for SQLite
- Application: Flask

## Results
The three key differences in weather between June and December:
- The max temperatures for both months are 85 and 83, respectively. 
- The min temperatures for both months are 64 and 56, respectively. The differences between the months are minute, thus, it appears the surf and ice cream shop business would be sustainable year round.
- There are 183 more data values for the month of June than December.

![june_temperatures](https://github.com/junepwk/surfs-up/blob/main/Resources/june_temperatures.png) ![dec_temperatures](https://github.com/junepwk/surfs-up/blob/main/Resources/dec_temperatures.png)

Between the year 2016-2017, this histogram further shows that Oahu maintains consistent temperatures throughout the year ranging between high 60s and 80s. 

![temp_histogram](https://github.com/junepwk/surfs-up/blob/main/Resources/temp_histogram.png)

## Summary
As stated above, the weather in Oahu remains pretty consistent and moderate throughout the year making the location ideal for opening a surf shop that also serves ice cream. 

By looking at the precipiation data for the months of June and December, December experiences heavier precipitation with the max at 6.42mm.  According to [water.usgs.gov](https://water.usgs.gov/edu/activity-howmuchrain-metric.html#:~:text=Heavy%20rain%3A%20Greater%20than%204,than%2010%20mm%20per%20hour.), precipitation greater than 4mm but less than 8mm per house is considered heavy rain. About 75% of the data falls between 0.12-0.15mm for June and December, respectively.  So majority of the time, the locals at Oahu are experiencing very slight showers. 

![june_prcp](https://github.com/junepwk/surfs-up/blob/main/Resources/june_prcp.png)
![dec_prcp](https://github.com/junepwk/surfs-up/blob/main/Resources/dec_prcp.png)



