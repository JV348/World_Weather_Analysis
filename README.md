# World Weather Analysis
We used OpenWeatherMap and Google APIs to analyze the weather conditions in both hemispheres of Earth. With Jupyter Notebook, Python, and various packages, we delved into the data provided by the APIs and prepared information that was digestable for users. As a result of the data accrued and the software available, we then generated a simple app that showed the directions and weather information associated with cities that a client would like to travel to. 

## Project Overview 
As a tester and developer, it was requested that we first add the weather descriptions and, subsequently, filter the data for preferences. Afterwards, we developed a travel itinerary for four cities, with corresponding maps that showed conditions and directions to the listed cities in the itinerary. We were expected to use Google Maps Directions API for the latter portion, as the data for conditions had already been obtained in a previous work effort. Ultimately, two visual aides for a possible client were generated for a client who would like to visit Australia. 

Deliverable 1 : Retrieved the necessary information with an API call from OpenWeatherMap and added that data to a new dataframe. 

![Vacation_DF](https://github.com/JV348/World_Weather_Analysis/blob/c73efe4c14ee64d9be8e8b87e74132907c583ce5/Vacation_Search/WeatherPy_Vacation.png)



Deliverable 2 : Filtered that data for preferred temperatures, and added hotel information into the csv; then used a Google Maps API to generate a Customer Travel Desinations Map for the itinerary.   
NOTE - This map was zoomed in on with Jupyter Notebooks (the original map has hotel locations on various continents). 

![Marker_Map](https://github.com/JV348/World_Weather_Analysis/blob/d97fcdf498ca2497d7dd7bb64e15216f0a642ba9/Vacation_Itinerary/WeatherPy_travel_map_markers.png)



Deliverable 3 : Refactored code and chose 4 cities to isolate for a map with directions. Used Google Directions API to generate a Travel Itinerary Map for the client. 

![Travel_Map](https://github.com/JV348/World_Weather_Analysis/blob/d97fcdf498ca2497d7dd7bb64e15216f0a642ba9/Vacation_Itinerary/WeatherPy_travel_map.png)



### Resources 
- Data Source: WeatherPy_Vacation.csv
- Software: Python 3.6.7, Pandas, Jupyter Notebook
- Databases: Google APIs, OpenWeatherMap APIs

### Summary 
The objective was successful, as a script was generated to output the directions and conditions for four cities in Australia - those of Batesman Bay, Gold Coast, Bowen, and Yulara. The prospective client would begin and end the trip in Batesman Bay, which is conveniently located nearby the tourist attractions and airport of Sydney. Afterwards, they'd move on to Gold Coast where they would engage in surfing and sightseeing activites. Next would be Bowen, which is close enough to the Great Barrier Reef for a visit. Finally, the client would visit the desert for some sightseeing in Yulara, before returning to Batesman Bay for a rest (and a flight out of Sydney). 

In the end, we created a script that could execute what was required of us, and, more importantly, that could be easily refactored for more searches. 
