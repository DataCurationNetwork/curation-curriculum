# Module 0: Environment Setup Handout

This handout accompanies a slidedeck with the file name “0_Environment_Setup”

Last updated: 2024-01-31 1300

## Download the Example Dataset:

- [0_Environment_Setup_Datasets](https://drive.google.com/drive/folders/1yXnGJ2dV1WxI3Y8AH645kH5R1Zo3gTLK?usp=sharing) folder

  - Be sure to unzip the file

  - Note: this example datasets are derived from real datasets, but have been modified to highlight common curation issues.

## QGIS

### Download Instructions \[slides 3 - 7\]

1.  Go to the [Download QGIS](https://qgis.org/en/site/forusers/download.html) website: [https://qgis.org/en/site/forusers/download.html](https://qgis.org/en/site/forusers/download.html)

2.  Locate your operating system in the list of download options

3.  Please download the latest long term release. The long term release version of the program and the most stable at this time. By using this version of the program we will all see the same type of interface and there should be less confusion as we work through this workshop.

### Adding Vector Data \[slides 8-9\]

1.  Click on the “Open Data Source Manager” icon 

2.  When the “Data Source Manager \| Vector” dialog window opens, select “Vector” from the side menu

3.  Click on the three dots button to the far right of the “Source: Vector Dataset(s)” text entry box

    1.  This will allow you to browse for files

4.  Locate where the data layers are saved and select the SHP file extension

    1.  Select the file 0\_*study_area_cover_type.shp*

    2.  In a Shapefile there are multiple file extensions that are necessary for the program to correctly display the data, more details about Shapefiles is given in the Module 3: Common GIS Data Types.

5.  Click the “Add” button in the lower right corner

6.  Click the “Close” button in the lower right corner to finish

### Adding Raster Data \[slides 10-11\]

1.  Click on the “Open Data Source Manager” icon 

2.  When the “Data Source Manager \| Raster” dialog window opens, select “Raster” from the side menu

3.  Click on the three dots button to the far right of the “Source: Vector Dataset(s)” text entry box

    1.  This will allow you to browse for files

4.  Locate where the data layers are saved and select the correct file type

    1.  Holder the “Shift” key to select the files 0\_*warblerProductivity.tif* and 0\_*woodcockProductivity.tif*

5.  Click the “Add” button in the lower right corner

6.  Click the “Close” button in the lower right corner to finish

### Check Layer Properties \[slides 12-13\]

1.  Right click on the name of the layer you wish to check

    1.  Select the file 0\_*study_area_cover_type* layer

2.  Select “Properties” from the pop-up menu

3.  Select “Information” from the side menu of the Layer Properties window

    1.  This will show you information and metadata about the layer

### Look at Attribute Table \[slides 14-15\]

1.  Right click on the name of the layer you wish to check

    1.  Select the file 0\_*study_area_cover_type* layer

2.  Select “Open Attribute Table” from the pop-up menu

### On-the-Fly Projection Change \[slides 16-17\]

1.  Right click on the name of the layer you want to change and go to “Layer CRS”

    1.  For this example we will change the projection of all three layers, one at a time

2.  Click on “Set Layer CRS”

3.  Search for the projection you need or select from the recently used list

    1.  For this example search for EPSG:26915 - NAD/UTM zone 15N

4.  Click OK

    1.  Repeat “Set Layer CRS” for each layer you have opened.

5.  When the layers disappear don’t panic. Right click on the name of the layer and select “Zoom to Layer” to recenter the layer in your view.

### Save Layer in New Projection \[slides 18-19\]

1.  Right click on the name of the layer

    1.  For this example we will change the projection of all three layers, one at a time

2.  From the pop-up menu select “Export” and then “Save Feature As…”

3.  Use drop down menu for “Format” to choose appropriate file format

4.  Use the three dot button next to “File Name” text entry box to rename the file and place it in the appropriate folder

    1.  We suggest using same naming convention and adding the new projection name at the end of the file name (example: 0_study_area_cover_type_UTM15N)

5.  Click on globe icon to the right of the CRS dropdown menu to find the appropriate projection

    1.  Use the EPSG:26915 - NAD/UTM zone 15N projection for this example

6.  Choose a transformation option that best fits your situation

    1.  For this example simply click “Okay” when asked

## ArcPro \[slides 20-23\]

### Download/Login Instructions

1.  Check to see if your institution has a license for Esri ArcGIS Pro

    1.  If you do not have an account try using QGIS

2.  Request an account from the department holding the license

3.  Follow the [download instructions](https://pro.arcgis.com/en/pro-app/latest/get-started/download-arcgis-pro.htm) for the program from Esri: [https://pro.arcgis.com/en/pro-app/latest/get-started/download-arcgis-pro.htm](https://pro.arcgis.com/en/pro-app/latest/get-started/download-arcgis-pro.htm)

### Adding Vector Data \[slides 24-25\]

1.  Click on the “Add Data” icon

2.  Click on “Data - Add Data to Map”

3.  Locate where the data layers are saved and select the correct file type

    1.  Add the vector file 0\_*study_area_cover_type.shp*

### Adding Raster Data \[slides 26-27\]

1.  Click on the “Add Data” icon

2.  Click on “Data - Add Data to Map”

3.  Locate where the data layers are saved and select the correct file type

    1.  Add the Raster files 0\_*warblerProductivity.tif* and 0\_*woodcockProductivity.tif*

### Check Layer Properties \[slides 28-29\]

1.  Right click on the layer

2.  Select “Properties” from the pop-up menu

### Look at Attribute Table \[slides 30-31\]

1.  Right click on the layer

    1.  Select the file 0\_*study_area_cover_type* layer

2.  Select “Attribute Table” from the pop-up menu

### On the Fly Projection Change \[slides 32-33\]

1.  Right click on the “Map” and select “Properties”

    1.  For this example we will change the projection of all three layers, one at a time

2.  Choose the “Coordinate Systems” Tab

3.  Search for the coordinate system

    1.  For this example search for EPSG:26915 - NAD/UTM zone 15N

4.  Click “OK”

### Save Layer in New Projection \[slides 34-36\]

Now if the layer needs to be saved in the correct projection we suggest
you ask the researcher to transform the file for you to ensure it is
done correctly. However, if they do not know how you can provide them
these basic steps to get them started.

1.  Under “Analysis” tab select “Tools”, in the catalog pane a Geoprocessing pane will open

2.  Search for “project” in the search bar and select the correct tool

3.  A form will appear, put the existing layer in the “Input Dataset or Feature Class box”

4.  In the “Output Dataset or Feature Class” use the button to navigate to the folder you wish to save the new layer too and give the file a unique and descriptive name

    1.  We suggest using same naming convention and adding the new projection name at the end of the file name (example: 0_study_area_cover_type_UTM15N)

5.  Click on the Globe button and search for the new coordinate system/projection

    1.  For this example search for EPSG:26915 - NAD/UTM zone 15N

6.  Click Run

7.  Check new layer is in the correct projection under “Properties”
