# Earthquake_Challenge

## Overview & Purpose

The purpose of this project was to build visualizations with interactive features of earthquakes from around the world. I retrieved the latest 7 days of earthquake GeoJSON data from the US Geologic Survey website using JavaScript and D3 and Leaflet libraries, and then plotted the data on a mapbox map through an API request.

## Results

The magnitude and location of each earthquake is shown in a popup marker. The size and color of the marker reflects the earthquake’s magnitude. Fault lines were added to the map to illustrate the relationship between the location and frequency of seismic activity and tectonic plates.

The final composite map looks like this:

![pop up marker](https://user-images.githubusercontent.com/97558998/170738854-bb3bd921-3ffa-47e9-9fb9-57c86ba54553.png)

Satellite map layer:

![Satellite_view](https://user-images.githubusercontent.com/97558998/170738189-a5f78264-e765-49b1-a2b0-fc7a11d044f2.png)

Dark map layer:

![Dark_veiw](https://user-images.githubusercontent.com/97558998/170738226-26edd55b-33c2-4566-8182-98c7c78fd939.png)

Major earthquakes only:

![Major_earthquakes](https://user-images.githubusercontent.com/97558998/170738253-62667eaa-9bca-40a1-a281-f5e9af2d735f.png)

All earthquakes:

![All_earthquakes](https://user-images.githubusercontent.com/97558998/170738288-d90011bf-9bcb-471b-baf7-56da4b52a17d.png)

Tectonic plates only:

![Fault_lines](https://user-images.githubusercontent.com/97558998/170738383-95568839-b3dd-4f7f-8d5c-32e650f51015.png)

## Summary

This visualization shows that major earthquakes in the last seven days have occurred on or near a tectonic plate; smaller earthquakes may occur farther away. It would be interesting to research the cause of the smaller earthquakes!
