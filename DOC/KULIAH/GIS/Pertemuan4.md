Background

Spatial data is data that implements a space that source information is highly luas.Seperti the previous article of data that we use to process the data that is natural earth, while the software used here for example QGIS.

Discussion

Preparing spatial data, we can take in the natural earth spatial data.
Spatial Data Processing, processing or retrieving spatial data must use tools or tools eg QGIS but we will do a demo using the CMD already installed python
Steps megolah spatial data using python:
we import shapefile library
 
>>> Import shapefile
Then we declare the variables that we use, now can we replace its own variables as you wish. Then we call the shapefile library and read the file extension shp.

>>> Sf = shapefile.Reader ( 'namafile.shp')
Once we call the file extension shp then we will use the commands to determine the contents of the data contained in the file shp
eg:

+ Sf.fields -> function to see the number of columns.

+ Sf.records-> function to see the amount of data.

+ Sf.record (2) -> function to view data on line 2.

+ Sf.shapes-> function to view the content of shapefile.

+ Sf.shape (2)> function to view the content of shapefile on line 2.

Conclusion

kesimpulanya so that we can take is that we can choose to process the data with python shapefile data and we can find the data that we choose.
