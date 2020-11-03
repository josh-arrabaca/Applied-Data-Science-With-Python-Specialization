Region: Ann Arbor, Michigan, USA
Domain Category: Weather phenomena


Question: Is there a relationship between the number of daily flight operations and the daily wind speed at Ann Arbor Municipal Airport?

The data comes from two sources:
The Federal Aviation Administration Operations Network (FAA OPSNET) - https://aspm.faa.gov/opsnet/sys/airport.asp
The National Oceanic and Atmospheric Administration - National Centers for Environmental Information (NOAA) - https://www.ncdc.noaa.gov/cdo-web/datasets/LCD/stations/WBAN:94889/detail

The FAA data contains the number of daily flights in Ann Arbor Municipal Airport, from 2015 to 2019.
The NOAA data contains daily weather data from the Ann Arbor Municipal Airport, and includes temperature (in F), precipitation(in inch), and wind speed(mph)



The visualization chosen is the scatterplot since it is a good representation of the X&Y relationship without assuming that a regression line can be immidiately built. In this case, we are asking whether there is a relationship between daily wind speed and daily flight operations at Ann Arbor Municipal Airport.

The plot shows a slight inverse relationship (as wind speed increases, the number of daily flights go down), however the spread of the points indicate that this is not always the case. Calculating for the correlation coefficient shows only a value of -0.34, indicating a weak negative relationship. The average daily precipitation (of rain or snow) is also shown as the point colors and sizes, but this also does not show a clear trend.

We can only therefore conclude that there is a weak relationship between wind speed and daily flight operations at Ann Arbor Municipal Airport.

Design Principles used in the Graph:
* Truthfulness - All of the days from 1st Jan 2015 to 31st Dec 2019 are represented as points in the scatterplot, and the graph is not skewed nor scaled to show a relationship that doesn’t exist.

* Beauty - The graph uses a cool blue and red color palette to make it easier to look at the points despite the chaotic spread of the data.

* Functionality - A third dimension (daily precipitation) is used to increase or decrease the size of the points, and through this it can easily be seen that there is no discernable relationship between precipitation and daily flight operations.

* Insightfulness - The graph makes it easy to see a somewhat inverse relationship between wind speed and daily flights, but the spread of the graph suggests that other factors should be considered for future projects to clearly see the relationship between flights and weather (for example, focus only on commercial flights and exclude military flights, include daily temperature, and other possible data.)

