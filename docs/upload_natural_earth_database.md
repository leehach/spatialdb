# Uploading the Natural Earth Database to PostGIS

These instructions assume that you have followed the instructions on this site to [create a PostGIS server in Docker](creating_a_postgis_server_in_docker.md). If you are using a different PostGIS server, you will need to modify the connection string to connect to your actual database.

This also assumes that you have `ogr2ogr` installed. On Windows, this can be installed as part of OSGeo4W. (The PSM laptops already have OSGeo4W installed.) Instructions for Mac/Linux will vary.

1. Download the [Natural Earth GeoPackage](https://naciscdn.org/naturalearth/packages/natural_earth_vector.gpkg.zip) [large file, currently 436 MB].
2. Unzip the downloaded folder. The actual `natural_earth_vector.gpkg` file is in a subfolder of a folder, unhelpfully also named `natural_earth_vector.gpkg`. Note the location of the actual GeoPackage, or copy it to a location of your choice.
3. Connect to your PostGIS server using your management client (e.g., DBeaver). Create the `natural_earth` schema. This can be accomplished using management client tools, or by running the SQL statement `CREATE SCHEMA natural_earth;`
4. Open OSGeo4W Shell (Windows) or the terminal (Mac/Linux). Change directory (`cd`) to the folder that contains `natural_earth_vector.gpkg`.
5. Use `ogr2ogr` to load the data into Docker PostGIS database:
    
    ```bash
    ogr2ogr -f PostgreSQL PG:"host=localhost port=5433 dbname=gis user=docker password=docker" -lco SCHEMA=natural_earth -nlt PROMOTE_TO_MULTI natural_earth_vector.gpkg
    ```
    
    This statement should take 5 minutes or so to run.

**NOTE:** `PROMOTE_TO_MULTI` is necessary in order to accommodate mixed polygons/multipolygons in some of the vector layers (the import will fail without it). While multipolygons are very common, multilines and multipoints are less common. Unfortunately this command will also import all the points and lines and multipoints and multilines. If you don't want to do this, you will have to import specific layers from the GeoPackage. The benefit of doing it the way we are doing is that we are able to import all 135 layers in the GeoPackage in one go.
