
<div id="bootcamp"><img style="display: none;" src="https://static.bc-edx.com/data/dl-1-2/m6/lms/img/banner.jpg" alt="lesson banner" />

### Background

In this challenge, we were tasked with completing two assignments to answer the fundamental question: "What is the weather like as we approach the equator?" The instructions for the assignments were as follows:

#### Part 1: WeatherPy

In this assignment, we completed a series of tasks to create a python script to visualize the weather from over 500 cities of varying distances from the equator using the citypy Pythno library and the OpenWeatherMap API

##### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill this first requirement, we used the OpenWeatherMap API to retrieve data and showcase in a series of scatter plots the following relationships:

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

##### Requirement 2: Compute Linear Regression for Each Relationship

To fulfill the second requirement, we computed the linear regression for a series of relationships and plotted these regression lines on corresponding scatter plots and determined r squared values. These relationships included:

* Northern Hemisphere: Temperature vs. Latitude

* Southern Hemisphere: Temperature vs. Latitude

* Northern Hemisphere: Humidity vs. Latitude

* Southern Hemisphere: Humidity vs. Latitude

* Northern Hemisphere: Cloudiness vs. Latitude

* Southern Hemisphere: Cloudiness vs. Latitude

* Northern Hemisphere: Wind Speed vs. Latitude

* Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, I explained my interpretation of what the linear regression modeled and described any relationships that I observed.

#### Part 2: VacationPy

In this section, we used the weather data that we generated in part 1 to plan future possible vacations to cities of interest on the list. Our main tasks involved using the Geoapify API and the geoviews Python Library to create interactive maps. Instructions as follows:

1. Create a map that displays a point for every city in the `city_data_df` DataFrame as shown in the following image. The size of the point should be the humidity in each city.

    ![Humidity map](https://static.bc-edx.com/data/dl-1-2/m6/lms/img/humidity_map.png)

2. Narrow down the `city_data_df` DataFrame to find your ideal weather condition.

3. Create a new DataFrame called `hotel_df` to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

     ![Hotel map](https://static.bc-edx.com/data/dl-1-2/m6/lms/img/hotel_map.png)