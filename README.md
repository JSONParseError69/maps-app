# Maps Clone

A simple map application built with **Mapbox GL JS** that allows users to view a map, search for directions, and interact with the map through zooming, rotating, and panning. This project serves as a basic clone of **Google Maps**.

## Features

- **Geolocation**: Automatically centers the map based on the user's current location.
- **Directions**: Users can input start and end locations to receive directions.
- **Interactive Map**: Allows zooming, rotating, and panning with controls.
- **Fallback Location**: Centers the map to a default location if geolocation fails.

## Getting Started

### Prerequisites

- A **Mapbox** account. You can sign up for free [here](https://account.mapbox.com/auth/signup/).
- A **Mapbox access token**. You can get it from your Mapbox account dashboard.

### Installation

1. Clone the repository to your local machine:

    ```bash
   git clone https://github.com/JSONParseError69/maps-app
    cd maps-clone
    ```

2. Open the `index.html` file in your browser to view the map.

### Usage

1. Replace the placeholder text `"YOUR_ACCESS_TOKEN_HERE"` in the `script.js` file with your actual **Mapbox access token**:

    ```javascript
    mapboxgl.accessToken = "YOUR_ACCESS_TOKEN_HERE";
    ```

2. Open `index.html` in your browser to see the map centered on your current location. If geolocation fails, the map will default to Manchester, UK.

3. Use the search bar on the top-left of the map to input directions from one location to another.

## File Structure

- **index.html**: The main HTML file that contains the structure of the map and includes the necessary styles and scripts.
- **script.js**: The JavaScript file that handles map setup, geolocation, and directions.

## Dependencies

- **[Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/)**: A JavaScript library for interactive, customizable vector maps.
- **[Mapbox Directions Plugin](https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-directions/)**: A plugin to integrate directions into your Mapbox map.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **[Mapbox](https://www.mapbox.com/)**: For providing the map tools and APIs.
- **Google Maps**: The inspiration for this clone.

