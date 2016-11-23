Background

As the material that we've discussed before we have discussed about the create shapefiles, well the next matter we will discuss about the edit shapefile. Perhaps many of us do not know how to edit and delete shapefile shapefile. The following discussion:

Discussion

How to edit the shapefile geometry data is as follows:
Open python at the command prompt
shapefile import
sf = shapefile.Editor (shapefile = 'toko.shp')
sf.poly (19,19,0,0)
sf.record ( 'Cake Shop', 'Dani')
sf.save ( 'shop')
How to remove the geometry data from shapefiles are as follows:
Open python at the command prompt
shapefile import
e = shapefile.Editor ( 'toko.shp')
e.shape (1) -> to record how much
e.delete (1)
e.save ( 'shop')
Conclusions and recommendations

Thus, the conclusion that the geometry data from shapefiles we can edit and delete data shapefiles that we make
