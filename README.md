# World_Weather_Analysis

## Overview
The purpose of this project is to retrieve a random set of coordinates, find the nearest city and the weather in that city. We then made a map with travel destinations, using the cities from our search. Of all of those cities, we chose four cities in the Pacific Northwest of the United States and built a driving route between the cities with Google Maps. We also added markers for the hotels and weather for those locations.

### Main Deliverables:
1. Retrieve Weather Data: Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data we gathered in this module, we then use our API skills to retrieve the current weather description for each city. Then, we create a new DataFrame containing the updated weather data and save the DataFrame as a csv file. 
2. Create a Customer Travel Destinations Map: Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
3. Create a Travel Itinerary Map: Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

## Output

Here's a screenshot of the vacation map created for our second deliverable:
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/103781847/170889515-d2cb17f6-d409-4f12-922d-8fc33660d9b0.png)

Here are screenshots of the itinerary we created for our thir deliverable. The itinerary is for a trip through four cities in the PNW (North Bend, Jackson, Eureka, and Fortuna). The directions are for a driving route and we pulled up hotels and the weather in each city as well.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/103781847/170889584-a0a1df02-4001-402f-b6cc-d06d54f85281.png)
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/103781847/170889588-a4c08826-ace5-4b4b-ace8-e742b6d31c7f.png)

----
