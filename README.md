
# Plan my trip 

## Introduction
This project aims at creating an application that will recommend where people should plan their next holidays based on weather and hotels data, and a list of the top 35 cities to visit in France.

The approach to build the application is:

- Scrape fata from each destination
- Get weather data from each destination
- Get hotels' info about each destination
- Set criteria for selecting a destination
- Generate recommendations


## Data
### COVID-19 data for the city of Chicago by ZIP code, by week
- [Nominatim API](https://nominatim.org/): to get the gps coordinates of all the cities (no subscription required)

- [OpenWeatherMAP API](https://openweathermap.org/appid): (you have to subscribe to get a free apikey) to get some information about the weather for the 35 cities and put it in a DataFrame

- [Booking][booking.com]: to scrape hotels for the best potential destinations

## Files
- **plan_my_trip.ipynb**: jupyter notebook containing all the steps of the app
- **booking.json**: json file containing informations about hotels in possible destinations
- **trip.csv**: file with top destinations and best 10 hotels in the area
- **requirements.txt**: list of dependencies to install