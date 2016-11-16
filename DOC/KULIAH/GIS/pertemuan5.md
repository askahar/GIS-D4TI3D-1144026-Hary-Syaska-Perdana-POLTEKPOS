Background

As the material that we've discussed before we have discussed about retrieving geospatial data, now the matter further we will discuss about the create shapefiles. Perhaps many of us do not know how to create shapefiles. Pembahasanya following:

Discussion

How to create shapefiles using python as follows:

The first to do that 'import shapefile'
and then after that we enter the variable with initialization, such as a variable to shapefile.writer then format -> 'a = shapefile.writer ()'
when we do create shapefiles that there are two formats that are used are:

SHP, in SHP format, there are three types of shapefiles namely Point, Polyline, and Polygon. Example: shp -> a.point (x, y), a.poly [(x, y), (v, w)]
DBF, in the DBF format, there are three fields that are used. Field 1 contains attribute tables, fields to 2 contains methods that are used and the field to three serves to save the shapefile name previously entered. Example: dbf -> a.field ( 'name.field', 'c', '40') a.record ( 'bdg')
Geospatial data is stored using a method a.save ( 'file.shp').

Explanation of methods used:

Point (x, y): entering data into shp shaped point and all data should be is formatted ESRI.1
Poly [(a, b), (c, d)]: insert geospatial data-shaped polygon or polyline.
Field ( 'name', 'c', '40'): it means making the polygon attribute table 'name' with varchar data type with a length of 40. This method can be repeated and can be made to the needs of the new field again.
Record ( 'bdg'): fill the table with only one field value 'Bandung'.
Save ( 'nama.file'): save file to save the file.
How to add the Record:

The first way to add record made at Point = 'a.point (x, y)' or 'a.point (x, y, 0,0)' with domain x and y are the coordinates
Then, on polyline = 'a.poly (shapefile = 3 parts = [[[x1, y1, z1, w1], [x2, y2, z2, w2], [......]]])'
In recent Polygon = 'a.poly) shapefile = 5, parts = [[[.......], [.......]]])'
Conclusions and recommendations

Thus, the conclusion that when making create shapefiles that we must understand that 2 format in shapefile create SHP and DBF, besides the method and also record to be added.
