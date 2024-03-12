# leaflet-challenge
This project provides a web-based visualization of recent earthquake data using interactive mapping technologies. It harnesses the power of Leaflet.js for mapping, D3.js for data manipulation, and the United States Geological Survey (USGS) Earthquake Hazards Program's API for real-time earthquake data. The main goal is to visually represent the magnitude and depth of earthquakes on a global scale over the past week, offering an intuitive way for users to understand the distribution and severity of seismic events.

Features:

-Dynamic Data Visualization: Automatically updates to reflect the most recent earthquake data from the USGS API.

-Interactive Map: Users can zoom in and out and navigate the map to explore earthquake events in different regions.

-Custom Markers: Earthquakes are represented by circle markers, where the size denotes magnitude and the color signifies depth, adhering to a predefined scale.

-Information Pop-ups: Clicking on a marker displays a pop-up with detailed information about the earthquake, including its magnitude, location, and depth.

-Legend: A map legend provides context for the marker colors, correlating them with earthquake depths.

Technologies Used:

-Leaflet.js: An open-source JavaScript library for mobile-friendly interactive maps.

-D3.js: A JavaScript library for manipulating documents based on data, used here to fetch and process the earthquake data.

-USGS Earthquake Hazards Program API: Provides real-time data on earthquake events, which is consumed by the application to display recent seismic activities.