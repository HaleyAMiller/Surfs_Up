# Surfs Up!

## Hawaii Weather Analysis Overview
#### Two business partners are considering creating and investing in a new passion project. The duo would like to open a surf and ice cream shop in Oahu, Hawaii. Before getting started with their business plan, they requested assistance in analyzing the practicality of the project to ensure its success. With weather data for multiple stations around Oahu, analyses were performed to gauge whether the shop would be a logical business strategy. Statistical analyses were run for the months of June and December to ensure the success of the store year round. Having data to support the feasibility of their store allows the business partners to utilize other investors as they have evidence to support the success of their passion project. 

## Resources Utilized
##### Data Source: Hawaii.sqlite
##### Software: Python 3.7.6; Anaconda 4.10.3; Visual Studio Code 1.65.0; SQLAlchemy 1.4

## Weather Analysis Results
#### Based on the SQLite data analyzed utilized SQLAlchemy, several results can be observed for June and December. Additionally, the statistics are displayed below with the June statistics on the left and December statistics on the right. Below are some observations noted by this analysis:
*	The standard deviation for June temperatures was 3.26 degrees while the standard deviation for December temperatures was 3.75 degrees, indicating a low level of variation amongst temperatures.

*	Despite having similar standard deviations, December minimum temperature was 56 degrees, almost 10 degrees lower than the minimum temperature in June (64 degrees).

*	The average temperature for December (71) is about 4 degrees lower than the average temperature for June (74.9).

*	The maximum temperature for December (83) is 2 degrees lower than the maximum temperature for June (85).


![June Temperatures](https://user-images.githubusercontent.com/99554642/164983169-8ea55815-f5ff-4975-b4a6-57b9c79f80ef.png)![December Temperatures](https://user-images.githubusercontent.com/99554642/164983183-25d3061d-4d82-46fd-b182-5fe81638cea4.png)


## Weather Analysis Summary
Despite the large difference in minimum temperatures, the temperatures for June and December were overall very similar with little variation and average temperatures in the 70’s. Likewise, the standard deviation for both months was about three degrees and maximum temperatures were only two degrees off. Based on temperatures alone, it would seem that the business would likely not be affected by the weather throughout the year. However, temperature alone only offers limited insight. Another query that could be beneficial for the business partners would be an analysis on the precipitation during different months as some consumers may not want to go surfing or eat ice cream during times of heavy precipitation. If more data were available, a query on wind speeds may indicate better days for surfing and a query on cloudiness might highlight times or seasons in which ice cream would be more popular. Another consideration would be for a query on tourism rates during different times of the year to ensure year-round business.
