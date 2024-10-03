#  Data Curation Network Lesson Plan: Curating Geospatial Data


| Lesson Components | Lesson Description |
| ------------- | ------------- |
| Data Type | Geospatial |
| Primary fields or areas of use | trans-disciplinary |
| Summary | This workshop is designed to introduce learners to the basic concepts of GIS and how this data is curated. Learners will be taken through initial steps of environment setup, introduction to GIS concepts, a review of common GIS data types, how GIS data is transformed, an overview of GIS metadata, and a discussion of the ethical considerations related to GIS data. This workshop includes lecture, hands-on activities, and discussion. |
| Estimated time | 5 Hours 30 minutes |
| Related primers | <li> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Geodatabase%20Data%20Curation%20Primer/Geodata-Primer.md">Geodatabase Primer</a></li><li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/GeoJSON%20Data%20Curation%20Primer/GeoJSON-data-curation-primer.md">GeoJSON Primer</a></li><li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/GeoTIFF%20Data%20Curation%20Primer/geotiff-data-curation-primer.md">GeoTIFF Primer</a></li><li> <a href="https://deepblue.lib.umich.edu/handle/2027.42/145724">netCDF Primer</a></li> |
| Link to slides | See links to slides and lesson plans in outline below |
| Date Created | October 2024 |
| Created By | Leighton Christiansen, OrcID: <https://orcid.org/0000-0002-0543-4268><LChristiansen@cdc.gov> Centers for Disease Control and Prevention, <https://ror.org/042twtr12>1600 Clifton Rd. Atlanta, GA 30329<br><br>Kelly Grove, <https://orcid.org/0000-0001-7926-169X><kegrove@fsu.edu> Florida State University, <https://ror.org/05g3dte14>222 South Copeland Street, Suite 424, Tallahassee, Florida 32306-1400<br><br>Melinda Kernik,  <https://orcid.org/0000-0002-1050-4152><kerni016@umn.edu> University of Minnesota, <https://ror.org/017zqws13> 309 S 19th Ave #0438, Minneapolis, MN 55455<br><br>Timothy Norris, <https://orcid.org/0000-0002-0898-3027> <tnorris@miami.edu> University of Miami, https://ror.org/02dgjyy92Coral Gables, FL 33124<br><br>Jennifer Moore, <https://orcid.org/0000-0001-6628-6820> <j.moore@wustl.edu> Washington University in St. Louis, <https://ror.org/01yc7t268>  1 Brookings Drive, St. Louis, MO 63130 |


# Objectives and Vocabulary

Learning Objectives:
1. Students can recognize Geospatial Data terms and have a tool for reference (glossary)
2. Students can recognize essential Geospatial metadata elements
3. Students are able to evaluate geospatial metadata and documentation
4. Students are able to differentiate between raster and vector data in the geodatabase
5. Students are able to use basic transformation tools to create open format files for sharing6. Students will be introduced to Ethical, Equitable, and Accessible geospatial data considerations

Terms to Know: Below are some key terms, a fuller list can be found in the list can be found in
[the Glossary](https://github.com/DataCurationNetwork/curation-curriculum/blob/main/Specialized%20Data%20Types/Geospatial/Glossary_of_GIS_Terms.xlsx)(first tab).
- Projection
- Datum
- Vector
- Raster
- Geodatabase
- Shapefile
- Feature Class
- FGDC
- ISO 19139 and 19115
- Attributes

# Dataset(s) for Lesson 

Required Tools/Software: a Geographic Information System (GIS) of some description, (e.g., [QGIS](https://www.qgis.org/en/site/), ArcGIS Pro) - this material emphasizes the use of QGIS.

Dataset Citations:

Harrison, Clement, A. C., Maranto, G. L., Purkis, S., Lombard, J. L., Clark-Hughes, A. C., Parrish, A. K., Reamer, M. B., Collins, O., Lewis, C., Cruz, M., & Solace, A. (2021). Data for Hyperlocalism: Transforming the Paradigm for Climate Adaptation study [Data set]. University of Miami. <https://doi.org/10.17604/p318-6n41>

Kramer, Gunnar R; Peterson, Sean M; Daly, Kyle O; Streby, Henry M; Andersen, David E. (2019). Data supporting the comparison of golden-winged warbler and American woodcock productivity in northern Minnesota, USA. Retrieved from the Data Repository for the University of Minnesota, <https://doi.org/10.13020/znag-tn48>.


# Outline and Content

Mode(s): all modes are indicated in the lesson plan for each module
Estimated time: 5 hours 30 minutes 

1. Environment Setup (Approximately 40 minutes)
This portion of the workshop deals with software setup. It is highly encouraged that the instructor(s) ask participants to download software prior to the workshop and dedicate some time at the start of the workshop to troubleshoot issues people may experience when downloading. It is also encouraged that there be a helper at each table for this portion of the workshop. <br>
	a. [Environment Setup Instructor Notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/0_Environment_Setup_Instructor_Notes.pdf) <br>
	b. [Environment Setup Slides](https://docs.google.com/presentation/d/1MudCrH6CtWErZ629jg31FsPcT7C_RpSagUTck7Lg-14/edit?usp=sharing)<br>
	c. [Environment Setup Handout](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Exercise%20Materials/0_Environment_Setup_Handout.pdf)

2. Introduction to GIS (Approximately 65 minutes) 
The objectives for this module are for learners to be able to describe a geographic information system (GIS); identify common tool sets for working with GIS data; describe characteristics of vector GIS data; describe characteristics of raster GIS data; conceptualize structure of a GIS project; understand the three principal components of a Coordinate Reference System (CRS).<br>
	a. [GIS Introduction Instructor Notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/1_GIS_Introduction_Instructor_Notes.pdf)<br>
	b. [GIS Introduction Slides](https://docs.google.com/presentation/d/1mEjOVsL4Qi4mFGqB7UVBlVsySj922GCm8yfg0QbS8T4/edit?usp=sharing)<br>
	c. [GIS Cheat Sheet Handout](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Exercise%20Materials/1_3_GIS_Cheat_Sheet.pdf)

3. Ethics and GIS Data (Approximately 45 min)
The objectives for this module are for learners to be able to identify where there would be ethical concerns when sharing geospatial data; provide recommendations for action when there are ethical concerns.<br>
	a. [Ethics and GIS Instructor Notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/2_Ethics_and_GIS_Data_Instructor_Notes.pdf)<br>
	b. [Ethics and GIS Slides](https://docs.google.com/presentation/d/1h2Yftz-GS7IybSLz84jAS74qxW87uUmIZ2Y3_vT8cic/edit?usp=sharing)

4. Common GIS Data Types (approximately 120 minutes [2 hours])
Common GIS Data Types. This module has many short activities for skill building, thus the module length. Participants are expected to have a GIS tool open during this module, and opening and exploring GIS files. The objectives for this module are for learners to be able to differentiate between raster data, vector data, and geodatabases; identify three common file formats for vector data; identify two common raster file formats; identify four common tools to open GIS data; gain an understand complex GIS file structures.<br>
	a. [Common GIS Data Types Instructor notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/3_Common_GIS_Data_Types_Instructor_Notes.pdf)<br>
	b. [Common GIS Data Types Slides](https://docs.google.com/presentation/d/1c7e3WgETTdr-to48phpXjEwqKQG6wkwbnrbn-gKv4rQ/edit?usp=sharing)<br>
	c. [Common GIS Data Types Cheat Sheet Handout](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Exercise%20Materials/1_3_GIS_Cheat_Sheet.pdf)

5. GIS Metadata (Approximately 50 minutes)
The objectives for this module are for learners to recognize essential geospatial metadata element; be able to evaluate geospatial metadata and documentation; prioritize reproducibility and usability over standards; locate where metadata is recorded in either QGIS or ArcGIS; name two GIS metadata standards.<br>
	a. [GIS Metadata Instructor notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/4_GIS_Metadata_Instructor_Notes.pdf)<br>
	b. [GIS Metadata Slides](https://docs.google.com/presentation/d/1Ksu-cU4N8dJZs6BLx0Q544rS9FndEw0M29TeTdVybx8/edit?usp=sharing) 

6. Transformations (Approximately 60 minutes)
The objectives for this module are for learners to understand common reasons for recommending transforming file formats; assess benefits and downsides of common file formats; be able to perform transformation of vector data in QGIS; be able to reproject a vector file in QGIS.<br>
	a. [Transformations Instructor Notes](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Instructor%20Notes/5_Transformations_Instructor_Notes.pdf)<br>
	b. [Transformations Slides](https://docs.google.com/presentation/d/1cQhxAH_psS5bi4s4CTgM5Z2r7RJfmtPyY8Z6A7zgAqI/edit?usp=sharing)

# Additional Resources 

[Glossary and Resources from Curricular Material](https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Geospatial/Glossary_of_GIS_Terms.xlsx)