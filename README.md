### World-Weather-Analysis

## Project Overview
This project consists on 3 technical analysis
  1. Retrieve weather data from different cities
    Generating 2k random latitudes and longitudes, we will retrieve the nearest corresponding           city and perform an API call with the OpenWeatherApp. For each city the weather info will be put into a dataframe.

  2. Create a customer travel destinations map
     We will ask specific conditions that the customer wants in order to retrieve a list of cities that make a perfect recommendation to travel to.
      
  3. Create a travel itinerary map
     According to each selected city a travel itinerary will be generated in order to plan the whole trip.
     
## Resources
Data Source:
- OpenWeatherApp
- Google Maps 

Software:
- Jupyter Notebook
- Python 3.7.6
- Anaconda 4.11.0
-Jupyter Notebook

## Results
# Retrieving Weather Data
A database according to the 2k latitudes and longitudes was created with the corresponding nearby city.

<img width="981" alt="Screen Shot 2022-02-13 at 10 36 48 PM" src="https://user-images.githubusercontent.com/83614893/153800857-4f53955e-238a-425c-b8f7-13792c74f3c3.png">

# Create a customer travel destinations map
With a reference from customer's preference travel destinations were suggested along with hotels.
![image](https://user-images.githubusercontent.com/83614893/153801015-8e931b06-7600-41b9-a071-6fe926e05f1d.png)

# Create a travel itinerary map
Google Directions API suggested a travel route based on the 4 cities that were selected for the trip
<img width="1372" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/83614893/153801132-9066b21b-0738-44e5-869a-6cd321955ba7.png">
