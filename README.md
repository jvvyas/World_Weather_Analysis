# World_Weather_Analysis

The impact of technology in tourism industry is evident. Through this analysis we can witness as to how a simple weather condition can influence the travel behavior and brings overall travel experience of an individual. This kind of exploratory analysis helps visualize weather data across cities worldwide and enhances the user interface and functionalities taking the travel apps more distinctive.                       

# Resources :

## Data Sources: 
- Weather_Database.csv
- WeatherPy_vacation.csv

## Software & Application Used :
- Matplotlib using Python library ver. 3.7.11
- Pandas/Jupyter Notebook : 6.4.6
- CitiPy,SciPy, Google and OpenWeatherMap APIs used with JSON Traversals
 
 
## Abstract

This project is conducted for PlanMyTrip, a top travel technology company. They have recommended few changes to be made in their app to take it to a next level :
This project will enhance the user interface and functionalities of the PlanMyTrip app with the following steps:

-	Retrieve weather data including the weather description for over 500 cities across the world
-	To create a customer travel destinations map
-	To create travel itineary map with real time data

## Results

-  Weather Data : The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).
The Python's citipy module is then called to identify the nearest city for each coordinate combination.
The weather data is retrieved for all identified cities through a request to the OpenWeatherMap API.
![image](https://user-images.githubusercontent.com/93893263/158030797-7739858d-8cb2-4957-ab64-b1e52d591c11.png)


- Travel destinations :With Jupyter's gmaps plugin, user's weather preference inputs and requests to the Google Maps and Places API, the app generates a customer travel destinations map.
![image](https://user-images.githubusercontent.com/93893263/158030438-7934b4f1-a5f7-4bae-94d3-2bd80bbbbe99.png)

- Travel Itineary :Using Google Maps Directions API the app generates a travel route between 4 cities selected by the user.
![image](https://user-images.githubusercontent.com/93893263/158030875-04cd94be-1e1f-4960-95a8-16eb0cbabdd8.png)




