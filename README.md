wineries-slo
============

Wineries subset for San Luis Obispo from 'A Nation of Wineries' http://www.nytimes.com/interactive/2013/07/07/business/a-nation-of-wineries.html

[data source](http://graphics8.nytimes.com/newsgraphics/2013/06/10/wine/cee6ef00993a2ff557062b67398e32f7bed9782a/data/wineries-locations.csv)>selected within San Luis Obispo County via [QGIS](http://qgis.org/) (Vector>Research Tools>Select by Location) and saved as [`wineries-slo.geojson`](https://github.com/oeon/wineries-slo/blob/master/wineries-slo.geojson)

I used [@aaronlidman](https://github.com/aaronlidman)'s [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson) to convert to .osm ...one small caveat, ampersand's had to be replaced with `and` (Find & Replace in a text editor) because JOSM was throwing and error upon opening the converted .osm. I load `wineries-slo-working.osm` for reference into JOSM and delete the points I have researched, reviewed and/or edited in OpenStreetMap; this file is temprorarily here only for my tracking purposes.

[`wineries-slo.csv`](https://github.com/oeon/wineries-slo/blob/master/wineries-slo.csv) is my progress
