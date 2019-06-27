# Python Weather Analysis

A Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using the OpenWeatherMap API.

The Jupyter Notebook generates a series of scatter plots to showcase the following relationships:

    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude

The script 

    Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
    Performs a weather check on each of the cities using a series of successive API calls.
    Includes a print log of each city as it's being processed with the city number and city name.
    Saves both a CSV of all data retrieved and png images for each scatter plot.


## OBSERVABLE TRENDS

1. The maximum temperature forms a bit of a bell curve around the equator (with the highest temperatures being found at or near 0 latitude). The curve trend is more complete for latitudes -40 to 70 and less data exists for further outlying latitudes (possibly because there are few cities on or near the south pole).

2. Cities at the equator appear to have higher humidity, while humidity levels closer to the poles (-90, 90) are more varied.

3. Wind speed appears to be greater near the poles and slightly more concentrated at lower speeds as cities near the equator.
