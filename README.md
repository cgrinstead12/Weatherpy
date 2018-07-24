# Weatherpy

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/Images/equatorsign.png)

In this example, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities. 

**Temperatures of Cities (Latitude)**

Using a get request from the OpenWeatherMap API, I was able to query the current temperatures of over 500 cities which are represented in the chart below by their associated latitude coordinate. Some of the observations we can make from this figure are that temperatures are at their highest when they are in closer proximity to the equator (0 latitude). As you get further from the equator and closer to the north and south pole, the temperatures decreases\. 

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/main/Chart%20Pictures/Temperature.png)

**Humidity of Cities (Latitude)**

In the next figure below, data points are plotted by their percentage of humidity and the cities latitude. One observation, while subtle, show that humidity tends to fall once the latitudes increase/decrease by 25 degrees. 

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/main/Chart%20Pictures/Humidity.png)

**Cloud Coverage of Cities (Latitude)**

In this figure no observable trends can be distinguished. I think cloud coverage would be best observed by location over time to be meaningful. 

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/main/Chart%20Pictures/CloudCoverage.png)

**Wind Speed of Cities (Latitude)**

When analyzing the winds speeds of each city, one could see that wind speeds typically did not exceed 20 mph. The majority of the data points were clustered closely together within the 0-10 mph interval. 

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/main/Chart%20Pictures/WindSpeed.png)

**Cities by Coordinates (Latitude & Longitude)**

In the last figure, the latitude data points help give the observer a more recognizable picture of what is going on since the data points are now plotted in what appears to be a world map. When compared to the first figure, the observation that temperatures increase as latitude points are closer to the equator become more clear. 

![alt text](https://github.com/cgrinstead12/Weatherpy/blob/master/main/Chart%20Pictures/Citiesbycoordinates_heatmap.png)
