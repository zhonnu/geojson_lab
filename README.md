# Sound Transit Link Light Rail Map

This repository contains a web application that displays the map and information of the Sound Transit Link Light Rail system in Seattle, Washington. The application utilizes Mapbox GL JS for map rendering and GeoJSON data for the rail lines and stations.

This is the lab 3 assignment of GEOG 328 in SUMMER 2023.

## Features

- Interactive map displaying the Sound Transit Link Light Rail system
- Information table listing the stations with their ridership data
- Sorting functionality to sort the stations by ridership
- Polygon overlay of the jurisdiction boundaries
- Custom styling for the rail lines and stations on the map

## Data Sources
The GeoJSON data used for the rail lines and stations is sourced from Sound Transit.

- link.geojson: GeoJSON data for the stations, including their names, coordinates, and ridership data (daily average in May 2023).
- line.geojson: GeoJSON data for the rail lines, including the coordinates for the line paths.
- jurisdiction.geojson: GeoJSON data for the Seattle jurisdiction boundaries.

## Technologies Used
- Mapbox GL JS: A JavaScript library for interactive, customizable maps.
- HTML: The structure and markup of the web application.
- CSS: The styles and layout of the web application.
- JavaScript: Handling data fetching, manipulation, and map interactions.

## License
This project is licensed under the MIT License.

## Acknowledgements
Sound Transit: For providing the GeoJSON data of the Sound Transit Link Light Rail system.
https://github.com/seattleio/seattle-boundaries-data/blob/master/data/city-limits.geojson: For providing GeoJSON data for Seattle city limit. 
