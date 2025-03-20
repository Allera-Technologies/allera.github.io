# allera.github.io
Public pages for Allera

## GeoJSON Maps
Helpful Links:
[MapShaper](https://mapshaper.org/) and [GeoJSON.io](geojson.io)

Metabase requires each file:
* Be less than 5 MB in size.
* Contain polygon features defining regions (not just points or coordinates). In my experience the points render strangely:
  ![image](https://github.com/user-attachments/assets/12ae5c05-690d-4336-8866-243c82a5696b)

* Use geographic coordinates (latitude and longitude) to define region polygons. Metabase doesn’t support projected coordinates, so you’ll need to convert projected coordinates to geographic coordinates.
* Be accessible by a public URL. Currently, you can’t upload a GeoJSON to Metabase.

More info [here](https://www.metabase.com/docs/latest/configuring-metabase/custom-maps).
