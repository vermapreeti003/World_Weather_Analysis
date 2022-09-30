## Overview
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

### Weather Database
This folder uses Open Weather Map API to pull weather information on over 720 different cities around the world. That information consists of:

Maximum Temperature
Cloudiness
Wind Speed
Humidity
Current Weather Description
These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.

### Vacation Search
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum and minimum temperature .
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/111541268/193350506-516a4a62-9367-4fea-964a-8bc51b8d0741.png)

### Vacation Itinerary
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Havre,Saint-Dizier,Saint-Francois,Semme.
![WeatherPy_travel_map](https://user-images.githubusercontent.com/111541268/193350565-5e776aa4-4f3d-4672-bb67-b24c7c87e807.png)

### Bonus: Weather Data
As an addon to these three folders, there is a weather data folder that has valuable linear regression models looking at the correlation between different weather infromation and latitude. These take into consideration the different weather information that are used in the weather database folder. 
