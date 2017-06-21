# mapnik-with-shapefile
render shapefile using mapnik
First, fetch datasource from OSM.  To manually create your datasource follow:

https://docs.oracle.com/cd/E35413_01/doc.722/e35412/ins_post_installation.htm#autoId10

You can also, fetch data from:

http://download.geofabrik.de/asia.html

download .osm.bz2 file. Then unzip  the file and rename it.

After that open python interpreter. Then create map and style it.
Now, give permission to the requried .shp file from your datasource so that it can be executed.  You can check permission status of your file using command: ll and then use:

chmod 777 /address of file/file.shp

create world.py file and copy code.
