ArcGIS Server on Docker

-Download ArcGIS Server for linux install

-Get an .ecp license file

-put both files in the same location as the Dockerfile

-build the Dockerfile

-run in a container

docker run -it -p 6080:6080 <imagename> bash

#inside container
cd /usr/local/arcgis/server

./startserver.sh

Open ArcGIS Manager and finish setup.