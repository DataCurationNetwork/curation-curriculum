# Module 0: Environment Setup Instructor Notes

\[This handout accompanies a slidedeck with the file name “0_Environment_Setup”\]

Last updated: 2024-02-08 1000

Lesson Plan: Environment Setup (~40 minutes)

## IMPORTANT NOTES:

This portion of the workshop deals with software setup. It is highly
encouraged that the instructor(s) ask participants to download software
prior to the workshop and dedicate some time at the start of the
workshop to troubleshoot issues people may experience when downloading.
It is also encouraged that there be a helper at each table for this
portion of the workshop.

It should also be noted that this slide deck does include instructions
for getting set up software and how to perform a few tasks in both QGIS
and ArcGIS Pro. This slide deck can be shortened to just one application
if instructors choose to focus on one. The slides pertaining to QGIS
specifically are 4 - 19 and slides focusing specifically on ArcGIS Pro
are 20 - 36.

Timing estimate of this module is based on showing one tool.

### Objectives:

- Install QGIS and/or ArcGIS Pro (if institution has Esri License)

- Load and display a vector dataset and a raster dataset

- Navigate the tools interface to perform tasks such as:

  - Check layer properties

  - Open attribute table

  - Change the projection of a layer

### Instructor Checklist:

- 0_Environment_Setup_Datasets folder found in the Module_Exercise_Datasets folder

  - Contains the practice datasets that are in the incorrect projection

- Copy of 0_Environment_setup slides

- Copy of Instructions for Environment Setup document

### Slide Notes: See slides

- When text is in BLUE it is a note or suggestion for the instructor

### Check Understanding

- Have students submit a:

	- Screenshots of the software downloaded to computer

	- Screenshot of a vector layer and a raster layer added to the layers list and displayed on map canvas.

 	 	- Can be two separate screenshots one for vector layer and one for raster layer

### Notes for Slides:

#### 1.  Welcome (30 seconds)

Timing estimate for this slide is a welcome to the
module not the workshop as a whole.

In this module we will be reviewing the interface of
QGIS or ArcGIS Pro (choose which one you want to focus on in this
workshop) and then we will practice adding two different data types and
performing a few necessary functions that would be common when checking
data at the start of the curation process.

#### 2. Module Objectives (1 minute)

In order to properly curate data we have to be able
to look at various aspects of the data. In order to do this we have to
be able to perform a series of basic checks to ensure the data is
properly described and can be opened.

#### 3. Download Example Dataset (1 minute)

For this module we will be using a dataset based on a dataset by Kramer
et al. on the comparison of golden-winged warbler and American woodcock
productivity in northern Minnesota, USA.

Please navigate to the 0_Environment_Setup_datasets folder and download
the dataset to your computer. We will be using the data for this folder
for this module only. The other activity folders will be used in later
modules and you will be prompted to download and access them as
necessary.

You might want to take a moment to explain the
structure of the example dataset folders.

Citation for full data set: Kramer, Gunnar R; Peterson, Sean M; Daly,
Kyle O; Streby, Henry M; Andersen, David E. (2019). Data supporting the
comparison of golden-winged warbler and American woodcock productivity
in northern Minnesota, USA. Retrieved from the Data Repository for the
University of Minnesota,
[https://doi.org/10.13020/znag-tn48](https://doi.org/10.13020/znag-tn48).

#### 4. QGIS (1 minute)

If the workshop is being taught using ArcGIS Pro you can skip to slide
20.

QGIS is an open-source GIS tool that works across a multitude of
operating systems (e.g. macOS, Microsoft Windows, Linux, and more). We
use QGIS to view, edit, analyze, and print geospatial data.

We will now go into touring the interface and walking through the steps
of performing a few functions

#### 5. Download Instructions for QGIS (30 seconds - 5+ minutes depending
on if downloads need to be done)

These are the instructions for downloading the program if the
participants have not been already prompted to do so. If everyone has
already downloaded the program without a problem feel free to skip this
slide. If there are still some who need to download the program we
suggest navigating to the QGIS website and show where the download
options are.

Then open QGIS on your computer in order to perform some live
demonstrations of tasks.

#### 6. QGIS Interface (1 minute)

This is a screenshot of the QGIS interface. We have broken it down into
4 main parts.

1.  Toolbars section - the shortcut icons to perform a variety of tasks

2.  File Connection List - An area where you can quickly connect to files and

3.  Layers List- In this area all of the GIS layers you add to the project will appear here. The order that they appear in this list is the order that they will be drawn on the screen. Meaning the top of the list will be the most visible and the bottom of the list will be the least.

4.  Map Canvas - This area is where the GIS layers will be drawn.

If you prefer you can also show these parts of the interface in the
actual QGIS application if you prefer that to the image.

#### 7. Important Toolbar Icons in QGIS (1 minute)

On the QGIS desktop the icons are often very small; it might be easier
for the participants to see which ones you are talking about if you use
the images on the slide provided.

Before we can start exploring data we need to become familiar with a few
icons that will be extremely helpful.

- Open Data Source Manager - allows you to add in GIS layers and other data

- Open Attribute Table - will display the attribute table for a given layer

- Identify Features - will allow you to click on an element of a layer and will give you the attributes just for that feature

- Pan Map - allows you to click and drag your screen to move to different areas of the map canvas

- Zoom to Full Extent - will zoom the map canvas area to full encompass a specified layer

- Zoom In - allows you to zoom in to the map canvas

- Zoom Out - allows you to zoom out on the map canvas

- Style Manager - is where the symbology of a layer can be set (used for changing color, line thickness, and more).

- Layer Labeling Options - allows to turn on and off labels for a designated layer

- Save - is used to save a project

- Open Project - is used to open an already existing QGIS project

- New Project - is used to open a new project workspace

- Pan Map to Selection - will zoom the map to the location of a selected feature in an attribute table

#### 8. Adding Vector Data in QGIS (4 minutes including demo)

Time to add our first set of data. We are starting with vector data and
will be using the file type Shapefile. These are the steps we are going
to follow and I will demonstrate.

1.  In the 0_Environement_Setup_Datasets folder there is another folder labeled 0_study_area_cover_type. In this folder are multiple file types all by the same name.

2.  Right now we are not going to go into all the types of files in this folder; for now just know that we want to use the SHP file type but these other files are important friends that tell the program how to read the SHP file.

Demonstrate adding the vector file 0_study_area_cover_type.shp to a
blank project.

#### 9. Adding Vector Data in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 10. Adding Raster Data in QGIS (5 minutes including demo)

Let’s add in a different data type. We are going to add raster data,
this type of data is read more as a grid of values. Raster data comes in
many file types for this exercise we will be using a .TIFF file. More
information about different raster data types is the module Common GIS
Data Types.

Demonstrate adding the raster file 0_warblerProductivity.tif and
0_woodcockProductivity.tif to a blank project.

#### 11. Adding Raster Data in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 12. Checking Layer Properties in QGIS (2 minutes including demo)

When we need to learn about a layer's “settings” and background we can
check the Layer Properties Dialog box. Here we can find some summarized
information and metadata about the layer. For example in a Raster we
should be able to find pixel size, extent, and so on. While in a vector
layer the layer properties window we could find general information
about setting to manage appearance and so on.

Demonstrate opening a layers properties window and pointing out a few
key pieces of information such as where to find the coordinate reference
system or pixel size.

#### 13. Checking Layer Properties in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 14. Look at Attribute Table in QGIS (2 minutes including demo)

Just as it is important to understand what data was collected and how,
we have to understand how the data is organized in these files. To do
this we are going to look at the attribute tables. The attribute table
displays information on features of a selected layer. Each row in the
table represents a feature (with or without geometry), and each column
contains a particular piece of information about the feature. Features
in the table can be searched, selected, moved or even edited.

Demonstrate opening a layer’s attribute table and pause for a moment to
look at the data contained in the table.

#### 15. Look at Attribute Table in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 16. On the Fly Projection Change in QGIS (6 minutes including demo)

Sometimes a researcher will give you files that are in different
projections. This can cause layers to not appear as you would expect for
example the dots do not plot where they should or if the layer can not
be seen with the others. We will discuss projection more in depth in a
different module. For now, think of it as drawing the layers on
different surfaces and when we try to combine those surfaces the drawing
does not line up. So it is ideal that all the layers have the same
projection.

You can do a quick “on the fly” projection change to see how the layer
would be drawn when in the same projection as the other layers. Now if
the layer needs to be saved in the correct projection we suggest you ask
the researcher to transform the file for you to ensure it is done
correctly. However, if they do not know how you can provide them the
basic steps, shown in the next demonstration, to get them started.

Demonstrate a quick change of projection of a layer. If you want you can
even turn on OpenStreetMap XYZ Tile to show the layer moving with a
point of reference layer underneath.

#### 17. On the Fly Projection Change in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 18. Save Layer in New Projection in QGIS (7 minutes including demo)

If the layer needs to be saved in the correct projection we suggest you
ask the researcher to transform the file for you to ensure it is done
correctly. However, if they do not know how you can provide them these
basic steps to get them started.

Demonstrate a change of projection of a layer and how to save it. If you
want you can even turn on OpenStreetMap XYZ Tile to show the layer
moving with a point of reference layer underneath.

#### 19. Save Layer in New Projection in QGIS (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

And with saving our layer to the project, we have completed the
demonstration of QGIS.

If you are not going to show ArcGIS Pro, you may jump to Slide 37 for a
review.

#### 20. ArcGIS Pro (1 minute)

Many higher education and government agencies have a license, you just
need to identify the point of contact who can give you a login. If your
institution does not have a license for ArcPro you can skip to slide 37.

ArcGIS Pro is a proprietary desktop GIS software developed by Esri.
ArcGIS Pro is replacing Esri's old desktop software called ArcMap.
ArcGIS Pro is notable in having a combined 2-D, 3-D support, ArcGIS
Online integration and Python 3 support. This is a very powerful tool
but does require a login from a purchased license.

The next few slides will be covering how to perform a series of
functions using the ArcGIS Pro interface.

#### 21. Download/Login Instructions for ArcGIS Pro (30 seconds - 5+
minutes depending on if downloads need to be done)

These are the instructions for downloading the program if the
participants have not been already prompted to do so. If everyone has
already downloaded the program without a problem feel free to skip this
slide. If there are still some who need to download the program we
suggest navigating to the Esri website and show where the download
options are. You may also need to demonstrate how participants can
receive a login from your institution.

Then open ArcPro on your computer in order to perform some live
demonstrations of tasks.

#### 22. ArcGIS Pro Interface (1 minute)

This is a screenshot of the ArcPro interface. We have broken it down
into 4 main parts.

1.  Ribbon Tab - the shortcut icons to perform a variety of tasks

2.  Contents Pane- Displays items related to the active view, which may be a map, a scene, a layout, or a view of the catalog

3.  Table View - Where maps, scene, and tables are displayed

4.  Catalog Pane - The items in a project can be managed here

If you prefer you can also show these parts of the interface in the
actual ArcPro application if you prefer that to the image.

#### 23. Important Toolbar Icons in ArcGIS Pro (1 minute)

On the desktop the icons can appear small; it might be easier for the
participants to see which ones you are talking about if you use the
images on the slide provided.

This is a list of some of the most used icons that will allow you to
interact with the data.

- Add Data - allows you to add spatial data or other types of data to a project

- New Map - creates a new map view within the project

- Explore (pan around) - allows users to click and drag around the table view area

- Zoom In- allows users to zoom in to the table view area

- Zoom Out- allows users to zoom out of the table view area

- Zoom to Full Extent - will zoom in or out to fit the entire layer on the screen

- Open Attribute Table - shortcut for opening a layers attribute table

- Select Feature - allows users to select a particular feature on the table view and receive a short summary of the feature

- Export Map - will export the map into other file formats such as a JPEG or others

#### 24. Adding Vector Data in ArcGIS Pro (4 minutes including demo)

Time to add our first set of data. We are starting with vector data and
will be using the file type Shapefile. These are the steps we are going
to follow and I will demonstrate.

In the 0_Environement_Setup_Datasets folder there is another folder
labeled 0_study_area_cover_type. In this folder are multiple file types
all by the same name. Right now we are not going to go into all the
types of files in this folder; for now just know that we want to use the
SHP file type but these other files are important friends that tell the
program how to read the SHP file.

Demonstrate adding the vector file 0_study_area_cover_type.shp to a
blank project.

#### 25. Adding Vector Data in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 26. Adding Raster Data in ArcGIS Pro (5 minutes including demo)

Let’s add in a different data type. We are going to add raster data,
this type of data is read more as a grid of values. Raster data comes in
many file types for this exercise we will be using a .TIFF file. More
information about different raster data types is the module Common GIS
Data Types.

Demonstrate adding the raster file 0_warblerProductivity.tif and
0_woodcockProductivity.tif to a blank project.

#### 27. Adding Raster Data in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 28. Checking Layer Properties in ArcGIS Pro (2 minutes including
demo)

When we need to learn about a layer's “settings” and background we can
check the Layer Properties Dialog box. Here we can find some summarized
information and metadata about the layer. For example in a Raster we
should be able to find pixel size, extent, and so on. While in a vector
layer the layer properties window we could find general information
about setting to manage appearance and so on.

Demonstrate opening a layers properties window and pointing out a few
key pieces of information such as where to find the coordinate reference
system or pixel size.

#### 29. Checking Layer Properties in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 30. Looking at Attribute Table in ArcGIS Pro (2 minutes including
demo)

Just as it is important to understand what data was collected and how,
we have to understand how the data is organized in these files. To do
this we are going to look at the attribute tables. The attribute table
displays information on features of a selected layer. Each row in the
table represents a feature (with or without geometry), and each column
contains a particular piece of information about the feature. Features
in the table can be searched, selected, moved or even edited.

Demonstrate opening a layer’s attribute table and pause for a moment to
look at the data contained in the table.

#### 31. Looking at Attribute Table in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 32. On the Fly Projection Change in ArcGIS Pro (6 minutes including
demo)

Sometimes a researcher will give you files that are in different
projections. This can cause layers to not appear as you would expect for
example the dots do not plot where they should or if the layer can not
be seen with the others. We will discuss projection more in depth in a
different module. For now, think of it as drawing the layers on
different surfaces and when we try to combine those surfaces the drawing
does not line up. So it is ideal that all the layers have the same
projection.

You can do a quick “on the fly” projection change to see how the layer
would be drawn when in the same projection as the other layers. Now if
the layer needs to be saved in the correct projection we suggest you ask
the researcher to transform the file for you to ensure it is done
correctly. However, if they do not know how you can provide them the
basic steps, shown in the next demonstration, to get them started.

Demonstrate a quick change of projection of a layer.

#### 33. On the Fly Projection Change in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 34. Save Layer in New Projection in ArcGIS Pro (8 minutes including
demo)

If the layer needs to be saved in the correct projection we suggest you
ask the researcher to transform the file for you to ensure it is done
correctly. However, if they do not know how you can provide them these
basic steps to get them started.

Steps continue on the next slide

#### 35. Save Layer in New Projection in ArcGIS Pro Continued

This is a continuation of the steps from slide 34. Demonstrate a change
of projection of a layer and how to save it.

#### 36. Save Layer in New Projection in ArcGIS Pro (Video Recording)

If you are comfortable demoing the steps from the previous slide you can
skip this slide. Or if you are unable to demonstrate the steps you can
play this slide as a demonstration.

Note: This video is not showing the example dataset listed at the start
of this module. The purpose of this video is to demonstrate the basic
steps necessary to perform the task.

#### 37. Module Objectives Review: Environment Setup (5 minutes depending
on size of workshop and how many helps can do the checks)

This is the check understanding step. It is suggested that all
participants either show the instructor or table helper (or can send in
screen shots) that show the application is installed and that they have
been able to successfully add a vector and raster layer into the
program.
