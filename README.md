# World_Weather_Analysis

## Overview of World Weather Analysis

The purpose of this project is to collect and present data for the **PlanMyTrip** website based on customer's preferred travel criteria entered into the search page. The results will provide the customer with their ideal hotel and current weather conditions anywhere in the world. 

In order to complete this request, we needed to use Jupyter Notebook and citipy module to obtain a list of random latitudes and longitudes. From there, using OpenWeather API, we retrieved the JSON weather data and added it to a Pandas Dataframe. This information was then used with Google Maps & Places API to build maps based on user's input. This map provided driving/bicycling/walking directions, as well as pop-up markers for hotels in the chosen areas. As practice, we also created heatmaps showing % humidity or % cloudiness.

**Example of Heatmap with % Cloudiness**
![heatmap](https://github.com/amylio/World_Weather_Analysis/blob/main/Images/HeatMap-Cloudiness.png)

**Example of Heatmap with PopUp Marker using Min/Max Temperature Parameters**
![heatmap](https://github.com/amylio/World_Weather_Analysis/blob/main/Images/Heatmap-withPopUpMarker.png)

## Results using Customer Input

When a customer inputs their weather criteria into the search field, the parameters will filter through the Dataframe to provide a list of Preferred Cities. Within this list, the following metrics are included in order to build maps to provide mode of transit directions, hotel recommendations and current weather conditions:

* City
* Country
* Latitude/Longitude Coordinates
* Max Temperature
* Current Weather Description
* Hotel Name

**User Temperature Criteria**

![temp](https://github.com/amylio/World_Weather_Analysis/blob/main/Images/MIn-MaxTempInput.png)

**List of Preferred Cities based on User Criteria:**

![Preferred City](https://github.com/amylio/World_Weather_Analysis/blob/main/Images/PreferredCityHotelName.png)

**Driving Directions**

![driving](https://github.com/amylio/World_Weather_Analysis/blob/main/MOD6%20Challenge%20Submission/Vacation_Itinerary/WeatherPy_travel_map.png)


**Hotel Recommendations**

![hotel](https://github.com/amylio/World_Weather_Analysis/blob/main/MOD6%20Challenge%20Submission/Vacation_Itinerary/WeatherPy_travel_map_markers.png)


