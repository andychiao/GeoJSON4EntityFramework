GeoJSON4EntityFramework
=======================
Create GeoJSON from Entity Framework Spatial Data

Add support for "LingString", "MultiLineString", "GeometryCollection", and Polygons with holes.<br />
Remove EntityFramework 5 support to simplify personal usage.<br />
Remove build in Json.Net serializer.<br />
Use System.Runtime.Serialization attributes to decorate properties needs to be serialized.<br />
You need plug your own Json serializer.<br />

GeoJSON Specs:
http://geojson.org/geojson-spec.html
