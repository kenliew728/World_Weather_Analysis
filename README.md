# **Travel Itinerary using API**
## **Objective**
The purpose of this challenge is to create a travel itinerary that allows user to view the travel route and weather description.

## **Method**
Three steps were followed to create a travel itinerary.

1. Step 1
   -  An API call was made to the OpenWeatherMap API to generate 2,000 random latitudes and longtitutes
   -  The latitudes and longtitudes were used to generate a list of cities with current weather description. 
2. Step 2:
   - Using retrieved data from Step 1, an API call was made to the Google Map API to generate a list of hotels within 5km of each city.
   - Next, a marker layer map with pop-up marker for each city was generated that contains the hotel name, city, country, and current weather condition. 
  3. Step 3:
      - The last step is creating a travel itinerary map that shows the route between four chosen cities.
      - This is possible by enabling the "directions API" on Google Map API. 

## **Summary**
The final product is a travel itinerary in the country of Malaysia where it will take a traveler around the country tour while enjoying great food the country has to offer and great summerlike weather!

![WeatherPy_travel_map](https://user-images.githubusercontent.com/70525492/96667811-64251d80-131f-11eb-9566-27e143f079dd.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/70525492/96667815-66877780-131f-11eb-80d5-d099cc19f872.png)
