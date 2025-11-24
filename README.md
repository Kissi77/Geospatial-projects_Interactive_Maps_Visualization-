Python Geospatial and Interactive Mapping Projects

This repository contains several geospatial projects in Python, demonstrating interactive maps, distance calculations, geocoding, and coordinate extraction.
The projects are beginner-friendly and practical for anyone learning Python geospatial analysis.

Project List & Features
Distance Calculation & Interactive Mapping (GeoPandas, Geopy, Folium)

Store cities using GeoPandas in a GeoDataFrame

Calculate real-world distance using Geopy's geodesic distance

Interactive Folium map with:

City markers

Polyline connecting cities

Automatic centering and zoom

Key Learning:

Working with GeoDataFrames

Real-world distance calculation

Interactive map visualization

Interactive Maps with Plotly & PyDeck

Choropleth maps highlighting countries using ISO-3 codes

3D globe visualization with PyDeck

Fully interactive (zoom, pan, rotate)

Key Learning:

Plotly choropleth visualization

3D geospatial visualization with PyDeck

Basic dashboard creation

3 Interactive Maps with Folium & Pandas

Visualize multiple cities and connections

Calculate distances between cities

Interactive markers and lines

Key Learning:

Map customization with Folium

Adding markers, lines, and popups

Combining geospatial data analysis with visualization

4️ Extracting Coordinates with ipyleaflet

Click anywhere on a map to extract latitude and longitude

Display coordinates using ipywidgets.Label

Add a marker at each clicked location

Key Learning:

ipyleaflet interactive map creation

Handling user interactions (click events)

Widgets for real-time coordinate display

5️ Geocoding & Reverse Geocoding with Geopy

Convert addresses → coordinates (geocoding)

Convert coordinates → addresses (reverse geocoding)

Handle errors gracefully using Python exception handling

Key Learning:

Nominatim geocoding API usage

Error handling for network or invalid inputs

Integrating geocoding with mapping projects

6️ Nearby Big Cities Map (Geopy + ipyleaflet)

Enter a city name and find nearby big cities within 200 km

Interactive map with:

Orange markers for nearby cities

Popups showing city names

Layer control for toggling visibility

Real-time distance calculations using great_circle

Key Learning:

Filtering cities by distance

Combining geocoding and mapping

Interactive visualization with labeled markers

 How to Run
Install Required Libraries
pip install geopandas plotly pydeck folium ipywidgets ipyleaflet geopy