# World_Weather_Analysis
Module 6
## Deliverable 1
For this Module 6 Challenge, I made a few changes to the PlanMyTrip App.  I added weather description into the city_data dataframe through an additional API request.
![weather_description_api](https://user-images.githubusercontent.com/45715246/210698000-b767bdb9-0e74-4b8c-8dd1-b95c3dcd695e.png)

## Deliverable 2
I created a preferred_cities dataframe to add user intput lines to allow the users in the app to decide their minimum and maximum temp preferences.  I added a hotel column to the dataframe to hold the names of the nearest hotels to each city within the parameters.  I created a CSV file WeatherPy_vacation.csv to hold the hotel list.  Then I created a map to hold the markers of each hotel in the database.
![WeatherPy_Vacation_map](https://user-images.githubusercontent.com/45715246/210699305-2105f267-cab4-40d0-9cbf-dbfad97c5223.png)

## Deliverable 3
For this section of the challenge I created a Travel Itinerary Map.  I accessed 4 of the cities from the WeatherPy_vacation_map and stored their information into an itinerary_df.  From that I created a waypoints_df with their longitude and latitude in order to make the route_map later.  I used Geoapify Routing API to create a travel route through these four cities.  I used the Geoviews path function to create a map that would hold the route.
![Screenshot_20230104_103327](https://user-images.githubusercontent.com/45715246/210699829-5364dba5-0396-4196-a706-df62fcd818d4.png)
