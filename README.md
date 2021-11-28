# World_Weather_Analysis

## Project Overview

Collect and analyze weather data across cities worldwide in order to allow PlanMyTrip to use the data to recommend ideal hotels based on clients' weather preferences.

**Goals:**

1. Collect the following data from the JSON file and add it to a DataFrame:
  
     City, country, and date; latitude and longitude; maximum temperature; humidity; cloudiness; and wind speed. 
     
     
2. Create scatter plots of the weather data for the following comparisons:
    
    Latitude versus temperature
    
    Latitude versus humidity
    
    Latitude versus cloudiness
    
    Latitude versus wind speed
    
    
3. Visualize Travel Data to create a heatmap for the new DataFrame and add  pop-up markers to the heatmap that display information about the city, current maximum temperature,      and a hotel in the city.


**##Resources**
-Data Source: https://openweathermap.org; https://developers.google.com/maps; https://jupyter-gmaps.readthedocs.io/en/latest/index.html
-Software: Python 3.7.10, Visual Studio Code, 1.38.1


**##Summary**

1. Collect the following data from the JSON file and add it to a DataFrame:
  
    City, country, and date; latitude and longitude; maximum temperature; humidity; cloudiness; and wind speed. 

    ![City_Data_Df](https://user-images.githubusercontent.com/92111396/143618839-691264a0-e51d-484e-ab4e-a6200823ba37.PNG)

     https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/City_Data_Df.PNG


2. Create scatter plots of the weather data for the following comparisons:
    
    Latitude versus temperature
    
    ![city_latitude_vs_max_temperature](https://user-images.githubusercontent.com/92111396/143619146-29f357c9-b0e2-46d1-9ac6-7ae9e7f9449c.png)

    https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/city_latitude_vs_max_temperature.png
    
    
    Latitude versus humidity
    
    ![city_latitude_vs_humidity](https://user-images.githubusercontent.com/92111396/143619157-072eb9e7-7e48-4687-9162-ad1de6a4849b.png)
    
    https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/city_latitude_vs_humidity.png
    
    
    Latitude versus cloudiness
    
    ![city_latitude_vs_cloudiness](https://user-images.githubusercontent.com/92111396/143619168-9f840999-72f2-44c6-96ec-99c07a24eaf8.png)

    https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/city_latitude_vs_cloudiness.png
    
    
    Latitude versus wind speed
    
    ![city_latitude_vs_wind_speed](https://user-images.githubusercontent.com/92111396/143619179-4bf99baa-dac3-44c0-850f-09aeaaf75319.png)

    https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/city_latitude_vs_wind_speed.png
    
    
3. Visualize Travel Data to create a heatmap for the new DataFrame and add  pop-up markers to the heatmap that display information about the city, current maximum temperature,      and a hotel in the city.

![Heatmap with Pop Up Markers](https://user-images.githubusercontent.com/92111396/143618355-ef823337-3ac8-481a-ba0c-e3b86fd4a98c.png)

https://github.com/mcbride249/World_Weather_Analysis/blob/main/weather_data/Heatmap%20with%20Pop%20Up%20Markers.png




**##Module 6 - Challenge** 

**##Purpose##**

The purpose of this challenge was to collect and analyze real world weather and mapping data using APIs. The information provided through the APIs would then be measured against users'preferred climate preferences across cities worldwide in order to allow PlanMyTrip to use the data to recommend ideal hotels to their clients' based on their own weather preferences. Beyond recommending a hotel , but similarly using the data proivided by APIs, travel and route data could be generated for these clients in order to provided them with a map and itenaray while travelling.  


**Deliverable 1**

Retrieve the following information from the API call:

Latitude and longitude; maximum temperature; percent humidity; percent cloudiness; wind speed; weather description.


**Deliverable 1 Results**

![Image 1 - WeatherPy Database](https://user-images.githubusercontent.com/92111396/143787204-20f3105d-4732-44fb-9b79-9e071ec2419e.PNG)


**Deliverable 2**

Retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.


**Deliverable 2 Results**

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/92111396/143787390-f4b1fb17-a3f6-4ca7-8033-7cd535ee1034.png)


**Deliverable 3**

Create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.


**Deliverable 3 Results**

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/92111396/143787463-4ed370eb-9905-4c3f-8510-0df6c641b63e.png)

