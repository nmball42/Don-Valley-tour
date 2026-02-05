# Mapping a historical tour of Sheffield’s Don Valley using uMap

Last updated: Feb 05th 2026

My brother Andrew wrote a [walking tour of the historical roots of the modern steel industry, Sheffield’s Don Valley](https://andrewsnotepad.blogspot.com/2026/01/the-lower-don-valley-history-tour.html) for his blog.

The open-source software uMap with an OpenStreetMap base can be used to turn this into a visual tour with a map, walking route, text and photographs. uMap can be used similarly for any piece of writing that involves traveling around an area.

The map is available [here](https://umap.openstreetmap.de/en/map/don-valley_110284).

## Requirements

- Web browser

## Run

- Open web browser to https://umap.openstreetmap.de/en/map/don-valley_110284

## Improvements

To existing features

- Add pictures, e.g., wikicommons or https://mapcarta.com and text snippets from Andrew's blog to the map points using uMap's ability to embed these and show on mouse over / click
- More extensive symbology from uMap plugins, or make own symbols
- Add places of interest as polygons
- Have someone walk the route to confirm it is 100% correct

## Extensions

Add new features

- Create the route as a NetworkX DiGraph (directed network) object using OSMnx, also GeoDataFrame and `.gpkg` GeoPackage
- Add other routes or places of interest
