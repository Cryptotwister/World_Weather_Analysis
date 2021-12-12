# World_Weather_Analysis
PlanMyTrip is a top travel technology company that specializes in internet-related services in a hotel and loging industry. We were asked to help collect and present data for customers via the search page which they will then filter based on their preferred travel criteris in order to find their ideal hotel anywhere in a world.

#### Task:
Collect and analyze weather data across cities worldwide.
#### Purpose:
PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences. Create an itinerary with the chosen 4 destinations to visit and provide the driving route including hotels in those locations.

## Weather_Database:
Generated a set of 687 random latitudes and longitudes in [Weather_Database.ipynb](https://github.com/Cryptotwister/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data used API to retrieve the current weather description for each city ([WeatherPy_Database.csv](https://github.com/Cryptotwister/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)). Then, created a new DataFrame containing the updated weather data.

## Vacation_Search:
Used input statements to retrieve customer weather preferences in [Vacation_Search.ipynb](https://github.com/Cryptotwister/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb), then used those preferences to identify potential travel destinations and nearby hotels in [WeatherPy_vacation.csv](https://github.com/Cryptotwister/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv). Then, showed those destinations on a marker layer map with pop-up markers.

## Vacation Itinerary:
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
