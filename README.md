## Geospatial Data Visualization with GeoPandas and GeoPlot

This project demonstrates the use of geopandas and geoplot to visualize geospatial datasets, with tasks ranging from basic plotting to more advanced mapping techniques like kernel density estimation, cartograms, and choropleth maps. It includes examples of visualizing datasets in different formats, such as CSV, JSON, and SHP, and demonstrates how to create interactive and static maps using various projection systems like Web Mercator and Albers.
Project Tasks:

- Basic Map Plotting:
    - Plot world population data using the world.geojson dataset.
    - Visualize the area of US states using shapefiles with the EPSG:3857 CRS.

- Web Map with Elevation Data:
    - Create a base web map using Webmercator() projection and plot US cities' elevation data.

- Kernel Density Estimation (KDE) Map:
    - Plot KDE map for tree density in San Francisco using San Francisco datasets.

- Cartogram of New York City Population:
    - Visualize New York City’s population using a cartogram, stacking it with NYC precinct boundaries.

- US Tornadoes Interactive Map:
    - Plot interactive maps for tornadoes in the US for the years 2021 and 2022.

- Choropleth Map of US Population:
    - Create a choropleth map visualizing US population distribution.

- Stacked Map with Contextily:
    - Create maps with multiple layers, stacking a base map with points or boundaries using contextily and xyzservices.

Each task has been implemented in a Jupyter Notebook (geospatial_visualization.ipynb), which contains detailed code explanations and plots. This notebook provides a hands-on approach to learning geospatial visualization and covers various projections, classification schemes, and mapping techniques essential for geospatial analysis.
