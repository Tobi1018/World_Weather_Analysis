# World_Weather_Analysis
# Project Overview
In this project, we intend to collect, analyze, and visualize weather data across cities worldwide, in addition to providing travelers with a tool that will allow them to select a destination based on the weather. Using Google Maps Directions API, create a route between the four cities as well as a marker layer map.



## Delivery One 

In the delivery one, I generated a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data gathered in the module, I make use of API Knowledge to retrieve the current weather description for each city. Afterward, create a new DataFrame with the updated weather data.

![delivery_1](https://user-images.githubusercontent.com/58860105/134818496-37b9f83b-aa26-462a-a79f-9a5cd82bbb4a.png)





## Delivery Two

In delivery two, I make use of input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Created a marker layer map with pop-up markers that displays those destinations.


![delivey22](https://user-images.githubusercontent.com/58860105/134818813-f338b0ce-4d41-4898-b7e2-7c797814fc42.PNG)


![delivery2Capture](https://user-images.githubusercontent.com/58860105/134818757-fd3dc577-2af9-43ed-9021-1a239c991165.PNG)


## Delivery Three

In delivery three, I make use of Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Using the marker layer, create pop-up markers for each destination on the itinerary.

![image](https://user-images.githubusercontent.com/58860105/134818886-bec53658-eb64-45e8-829c-3faa2ea33833.png)

![image](https://user-images.githubusercontent.com/58860105/134818894-38e2c3bc-a6f5-4a64-9b56-0a8411fd3e43.png)

## Statistical Analysis 
Using the Linear regression

  * Latitude and Maximum Temperature
  * Latitude and Humidity
  * Latitude and Cloudiness
  * Latitude and Wind Speed


 
 ![image](https://user-images.githubusercontent.com/58860105/134819466-22765cdc-e913-4558-bf28-b34b858d0e41.png)
 
 ![image](https://user-images.githubusercontent.com/58860105/134819470-af27184f-42bb-4efe-a0b4-fa4937c0840e.png)
 

 
 ![image](https://user-images.githubusercontent.com/58860105/134819489-821b9bc5-59f5-4778-9631-740bee54844f.png)




## Scatter Plots

We make use of scatter plots to generate the parameter against the latitude of all cities. 

![image](https://user-images.githubusercontent.com/58860105/134819354-6f69f743-e8dd-414e-aea7-d00f26bbcdd0.png)

![image](https://user-images.githubusercontent.com/58860105/134819363-8b6d9807-d534-4e7a-b595-1f1824032f42.png)

![image](https://user-images.githubusercontent.com/58860105/134819370-ee126d95-6f80-4c8b-94fb-490c17027074.png)

![image](https://user-images.githubusercontent.com/58860105/134819375-61306cf6-7ee1-495b-bf6b-e44f01ece599.png)



# Resources used to Complete project Analysis

CSV Files: [WeatherPy_Database.csv](https://github.com/Tobi1018/World_Weather_Analysis/blob/main/Weather_Database.ipynb/WeatherPy_Database.csv)

Jupyter Notebook Files: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

Python: Python Dependencies: Pandas, Matplotlib, CitiPy, Python Requests, APIs, JSON.
