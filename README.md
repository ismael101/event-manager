# Travel App

#### An application program which help the user to plan their travel trip by searching the events, restaurants, and weather for the city the user want to visit

## Program Display
![p1](https://user-images.githubusercontent.com/46719712/67989740-bbf3e180-fc01-11e9-96bd-71495aa67b59.JPG)

![p2](https://user-images.githubusercontent.com/46719712/67989786-e34aae80-fc01-11e9-8b04-f4a2b23d18d6.JPG)

![p3](https://user-images.githubusercontent.com/46719712/67989793-e5ad0880-fc01-11e9-998d-eb051acccd55.JPG)

![p4](https://user-images.githubusercontent.com/46719712/67989796-e776cc00-fc01-11e9-8913-a0a8604f789f.JPG)

## Getting Started
#### Clone this project on to your own machine from the root directory, from the command line run
#### Macs python3 -m venv env | env/bin/activate
#### Windows PC python -m venv env | env/script/activate
#### Install the requirements run pip install -r requirements.txt
#### From the command line to load the keys run source env.sh

## Starting the Program
#### Upon running the application will prompt the user to either search for a new city, or show saved data about restaurants or events
#### If you choose to search for a new city, you will be prompted to enter a city, country code and event type, the application will than display a five day weather forecast and some top restaurants and events in the city of your choice
#### If you choose to show saved data you will be asked whether you want to view restaurants or events, it will read from the database to show you your saved data

## To Run Test
#### To test the event and restaurant database:
###### Python -m unittest test_event_db.py 
###### Python -m unittest test_restaurant_db.py
#### To test the event and restaurant API:
###### Python -m unittest test_api.py

## API Used
#### YELP API
#### Eventful API
#### OpenWeather weather API

