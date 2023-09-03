# GIS Server Notes
A place to capture notes, tasks, and other detritus about setting up a GIS server for our projects.

## Server Info
We've got a [QGIS server](https://www.qgis.org/en/site/about/features.html#qgis-server) deployed to gis.codefordayton.org. Currently, it only has sample data loaded.

You can see some of the sample data through queries like:

http://gis.codefordayton.org/cgi-bin/qgis_mapserv.fcgi?SERVICE=WMS&VERSION=1.3.0&REQUEST=GetCapabilities

and

http://gis.codefordayton.org/cgi-bin/qgis_mapserv.fcgi?MAP=/home/qgis/projects/world.qgs&LAYERS=countries&SERVICE=WMS&VERSION=1.3.0&REQUEST=GetMap&CRS=EPSG:4326&WIDTH=400&HEIGHT=200&BBOX=-90,-180,90,180

More to follow.
