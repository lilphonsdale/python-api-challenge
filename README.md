# python-api-challenge

Working with weather data from an API

# Description

In the first notebook, WeatherPy, the citipy and numpy libraries are used to generate a random list of coordinates and cities from all over the world.

These coordinates and city names are passed into an API call to get weather data for all of the cities. The Open Weather Map API tells us each city's temperature, humidity, cloudiness, wind speed and more.

All of this data is used to create a dataframe and pandas is used to plot the weather against the city's position. We then define a function to calculate linear regressions, and call that function to look at the effect of latitude on different weather characteristics in the northern and southern hemispheres. 

In the second notebook, VacationPy, we take our combined city, geolocation and weather dataset and use it to plot a map. These are our potential holiday destinations. 

We call on the geoapify API to find hotels in cities that match our ideal weather conditions, and then plot those hotels on a new map.


# Authors and Acknowledgment
Thank you to the instructor, TAs, google, stack overflow, citypy library, hvplots, documentation and tutors.
