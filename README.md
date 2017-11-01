# LabFourSubmission

## WMS

![](https://github.com/hannahfriedrich/autumn/blob/master/img/LabFour-OR_counties.png)

WMS url: http://localhost:8080/geoserver/LabFour/wms?service=WMS&version=1.1.0&request=GetMap&layers=LabFour:OR_counties&styles=&bbox=-124.56670504390223,41.991794810535794,-116.46326242572455,46.23731681568611&width=768&height=402&srs=EPSG:4326&format=image%2Fpng

## WFS

OR_counties.geojson located in assets folder and can be accessed [here][]

WFS url: http://localhost:8080/geoserver/LabFour/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=LabFour:OR_counties&maxFeatures=50&outputFormat=application%2Fjson

## Mapbox Basemap

Mapbox basemap I created was inspired by the changing colors of the trees around us here in Corvallis. I wanted to use a warm color palette to render the various colors of leaves. The detailed, curly Gothic fonts chosen were to be evoke a Halloween aesthetic. My favorite part of the map is the various shades of green and yellow present in the topography.

![](https://github.com/hannahfriedrich/autumn/blob/master/img/Fall.jpg)


[here]: https://github.com/hannahfriedrich/autumn/blob/master/assets/OR_counties.geojson
