# Liikennemerkit

Yksinkertainen visualisointidemo Turun kaupungin liikennemerkkidatasta.

Data yksinkertaistettu .shp-tiedostosta komennolla: `ogr2ogr.exe -f GeoJSON -sql "select geometry_d from turun_liikennemerkit_3877 where signtype='511'"  -lco RFC7946=YES suojaties.geojson turun_liikennemerkit_3877.shp`


# Lisenssi
 * Koodi: MIT 
 * Data: data &copy; [Turun kaupunki](http://www.lounaistieto.fi/blog/2016/03/30/turun-kaupungin-liikennemerkit/)[CC BY 4.0](https://creativecommons.org/licences/by/4.0/deed.fi">CC BY 4.0) 