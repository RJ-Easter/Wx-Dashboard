# Wx Dashboard

    This website is meant to display weather data, in full screen, on the TV in the livingroom of my RV. The weather data contains: National Frontal Patterns, Local Weather(Wx) Radar, Current: Temp, Dew Point, Humidity, Barometric Pressure, % Chance of Rain, and Sky Conditions, 1/2/3-Day Forcasts of High/Low Temp, Sky Conditions, and % Chance of Rain.

## Version Path
V0.1
- UI using HTML/CSS
- Basic Logic
    - Async/wait data pull-downs
    - Data formatting
    - Pushing data to UI @ 15min intervals

V0.5
- All previous features
- Configurable location (Zip)
(Later, I would like to add compatibility with: City/State, Country/Province, MGRS, Lat./Long.)
- Make forecast panels pretty
- Store captured weather data for later analysis
- Day/Night changing UI colors based on Sunset/Sunrise times pulled from some Astronomical DB

V1.0
- All previous features
- Implement everything in Django or Flash (To force a re-write and learn something new.)
- Completely clean front end code and clean/useful backend analytics

## Development
- Lang: HTML/CSS/JS
- To Do (V0.1):
    - [x] UI HTML Skeleton
    - [x] CSS basic style for initial dev.
    - [] JS hook-ups with HTML elements
    - [] JS data pull-down
    - [] JS data formatting
    - [] JS data push to HTML
    - [] Does the app run every 15min?