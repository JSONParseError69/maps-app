# maps-app
A simple map application built with Mapbox GL JS that allows users to view a map, search for directions, and interact with the map through zooming, rotating, and panning. This project serves as a basic clone of Google Maps.

Features
Geolocation: Automatically centers the map based on the user's current location.
Directions: Users can input start and end locations to receive directions.
Interactive Map: Allows zooming, rotating, and panning with controls.
Fallback Location: Centers the map to a default location if geolocation fails.
Getting Started
Prerequisites
A Mapbox account. You can sign up for free here.
A Mapbox access token. You can get it from your Mapbox account dashboard.
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/JSONParseError69/maps-app
cd maps-clone
Open the index.html file in your browser to view the map.

Usage
Replace the placeholder text "YOUR_ACCESS_TOKEN_HERE" in the script.js file with your actual Mapbox access token:

javascript
Copy code
mapboxgl.accessToken = "YOUR_ACCESS_TOKEN_HERE";
Open index.html in your browser to see the map centered on your current location. If geolocation fails, the map will default to Manchester, UK.

Use the search bar on the top-left of the map to input directions from one location to another.

File Structure
index.html: The main HTML file that contains the structure of the map and includes the necessary styles and scripts.
script.js: The JavaScript file that handles map setup, geolocation, and directions.

Dependencies
Mapbox GL JS: A JavaScript library for interactive, customizable vector maps.
Mapbox Directions Plugin: A plugin to integrate directions into your Mapbox map.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Mapbox: For providing the map tools and APIs.
Google Maps: The inspiration for this clone.
