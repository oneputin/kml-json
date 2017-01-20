# \<kml-json\>

convert kml/gpx to geojson

## from slide-kml

extracts equally rootTags "Style","Stylemap" and "Placemark"  
and geometry types : ['Polygon', 'LineString', 'Point', 'Track', 'gx:Track']

Non-style attributes are (?not?) included!

## from gpx

extracts equally "tracks","routes" and "waypoints" 

## modications

### API (togeojson.js)

- OK: enable import of selected geometry-types
- enable more properties/userdata to be imported !!

### WebComponent (kml-json.html)

- OK: add attribute "query", an object containing property "tags" with name(s) of geometry-tags to import

###  



