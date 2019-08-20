### h2gis
---
https://github.com/orbisgis/h2gis

http://www.h2gis.org/

```java

```

```sh
CREATE ALIAS IF NOT EXISTS H2GIS_SPATIAL FOR "org.h2gis.functions.factory.H2GISFunctions.load";
CALL H2GIS_SPATIAL();

CALL FILE_TABLE('/home/user/myshapefile.shp', 'tablename');

CALL SHPREAD('/home/user/myshapefile.shp', 'tablename');

CALL SHPWRITE('/home/user/newshapefile.shp', 'tablename');
```

```
```


