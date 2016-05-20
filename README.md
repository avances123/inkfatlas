
# Intro
Me estoy basando en este link

```
http://roel.derickx.be/hikingmap/index.html
```


# Para bajarse los datos de osm

```
http://download.geofabrik.de/
```



# Para meter los datos de osm en el postgis

```
osm2pgsql -d gis -s nepal-latest.osm.pbf --style /home/fabio/repos/openstreetmap-carto/openstreetmap-carto.style
```


# Para bajarse los DEM
## Page general

```
http://viewfinderpanoramas.org/Coverage%20map%20viewfinderpanoramas_org3.htm
```

## Todo el srtm 
Son 13 gigas de raster, es el que hay que usar fijo
```
wget -N -i links 
```



## Los contours ya hechos

```
http://opendemdata.info/
```

