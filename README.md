# Geosoft II 2014 Testdata Repository

Testdate repository for metadata and data that can be commented.

There is a subfolder for each standard or type of (meta-)data. Seminar groups are encouraged to fork this repo and save example documents to build up a database of test scripts.

## How this repo works

1. Fork the repo
2. Add a document
  1. Save it in the respective directory, or create a new directory
  2. Add the URL and the filename to the INDEX file in the format `http://the.url/tothe?document > filename.ext`. This allows other users to retrieve the original document as well as to insert the same testdataset into their comment databases.
3. Send a pull request (for a bunch of documents)

## Catalogs

This is a (to be extended and) somewhat sorted list of websites and resources that are or link to catalogs of geodata. The lack of a "one stop shop" for discovering geodata is one of the motivations behind creating a comments database for them!

* **http://www.spatineo.com/**
* http://gis.stackexchange.com/questions/6345/list-of-available-online-wms-services-weather-land-data-place-names
* http://geopole.org/
* http://inspire-geoportal.ec.europa.eu/discovery/
* http://catalog.data.gov/dataset?q=WMS&sort=score+desc%2C+name+asc
* http://www.eurogeoss-broker.eu/
* http://geoportal.org/web/guest/geo_home_stp
* http://www.geoportal.de/DE/Geoportal/geoportal.html?lang=de
* http://www.opengeospatial.org/blog/2034
* http://gis.stackexchange.com/questions/34775/is-there-an-exhaustive-searchable-catalog-of-all-gis-web-services-e-g-ogc-wms
* http://www.skylab-mobilesystems.com/en/wms_serverlist.html

## Tipps for Implementing the standards-related functions

* Focus on the four required attributes
* Most of the OGC standards effectively rely on the OWS Common specifiction, which should give you most of what you need

## License

All documents are under the license of the respective dataset owners or service providers. Please check each document before using it if it is compatible with your work.
