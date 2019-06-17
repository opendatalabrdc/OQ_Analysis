# Visualisation of Building Polygons with irregular Geometry

## Building polygons that contain irregular angles (ie. other then regular, orthogonal, quasi-orthogonal) 

Filtering an OSM Building Polygons file for buildings that deviate to a certain degree from Regular forms let's produce a Ratio Indicator of Non-Regular polygons and an output file for buildings to look at more closely to explain deviations from regular geometries.
<br/>**Quasi-orthogonal angles definition** : angles [ between 80 - 100 degrees (quasi right angle) , or 175 - 185 degrees (quasi straigth line) ] 
<br/>**Regular angles definition** : constant angle geoemetries [ average angle +- 10 degrees ] 

- 2019-06-12 City of Portsmouth, Virginia Building Footprints & Addresses 
<br/> **OSM Source file** : [Portsmouth Import project final-josm.osm 2019-06-12](source/2019_06_12_portsmouth_osm_imports_final_josm.osm.gz) copied from 
[portsmouth-osm-imports Github Repo](https://github.com/jonahadkins/portsmouth-osm-imports)
<br/> **Geojson Visualisation** : [15,516 Building Polygons with non Quasi-Orthogonal angles](geojson/2019_06_12_portsmouth_building_import_Polygon_with_angle_plus10deg_away_vs_ortho_90_180.geojson)
<br/>  15,516 buildings (32% of the Import project) are flagged for non-regular angles