# OpenStreetMap Tile server

Automated build repository for the OSM tile server used in
[SmartRoadSense](http://smartroadsense.it) project. Build instructions are inspired by
[this](https://switch2osm.org/serving-tiles/manually-building-a-tile-server-14-04/)
guide, and build from source code have been replaced by package and precompiled binaries,
where possible.

## Usage

In order to use the image you must link to a PostGIS database.
To configure the db connection parameters, edit `configure.py`.
Don't forget to import data in your database, for example using `osm2pgsql`.

## Contributors

* [Antonio Esposito](https://github.com/kobe25)
* [Michele Sorcinelli](https://github.com/michelesr)
