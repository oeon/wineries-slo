wineries-slo
============

Wineries subset for San Luis Obispo from 'A Nation of Wineries' http://www.nytimes.com/interactive/2013/07/07/business/a-nation-of-wineries.html

[data source](http://graphics8.nytimes.com/newsgraphics/2013/06/10/wine/cee6ef00993a2ff557062b67398e32f7bed9782a/data/wineries-locations.csv), filtered by State then selected within San Luis Obispo County via [QGIS](http://qgis.org/) and saved as GeoJSON.

I used @aaronlidman's [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson) to convert to .osm ...one small caveat, ampersand's had to be replaced with `and` because JOSM was throwing and error upon opening the converted .osm. I load the .osm file for reference into JOSM and delete the points I have edited in OpenStreetMap.
