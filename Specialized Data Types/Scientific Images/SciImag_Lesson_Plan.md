# Data Curation Network Lesson Plan: Curated Application for Scientific Images

| Lesson Components | Lesson Description |
| ------------- | ------------- |
| Data Type | Scientific Images |
| Primary fields or areas of use  | All |
| Summary  | This workshop introduces basic concepts of curating scientific images.<br><br> This workshop also provides an overview of the general CURATE(D) curriculum. |
| Estimated time  | 3 hours (not including breaks) |
| Related primers  | <li> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Confocal%20Microscopy%20Images%20Data%20Curation%20Primer/confocal-microscopy-images-data-curation-primer.md">Confocal Microscopy Image Primer</a></li><li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/GeoTIFF%20Data%20Curation%20Primer/geotiff-data-curation-primer.md">GeoTIFF Primer</a></li><li> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Human%20Participants%20Data%20Essentials%20Data%20Curation%20Primer/human-participants-data-essentials-data-curation-primer.md">Human Participants Data Essentials Primer</a></li><li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Neuroimaging%20DICOM%20and%20NIfTI%20Data%20Curation%20Primer/neuroimaging-dicom-and-nifti-data-curation-primer.md">Neuroimaging DICOM and NIfTI Primer</a></li><li> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/CARE%20Primer/care-primer.md">CARE Data Principles, Indigenous data, Data related to Indigenous Peoples and Interest</a></li> |
| Link to Slides  | <a href="https://docs.google.com/presentation/d/132W5LhMi3qazK1S60ihdSzLeiYCFNM-xonQWoCGuox4/edit#slide=id.g257084923a6_0_0">Scientific Images Slides Deck</a> |
| Date Created | June 2023 |
| Created By | Created by <br> The Pixels: <br> Sarah J. Wright, Cornell University, <a href="https://orcid.org/0000-0002-1502-131X">https://orcid.org/0000-0002-1502-131X</a><br> Mariah Kenney, Carnegie Mellon University, <a href="https://orcid.org/0000-0003-4884-108X">https://orcid.org/0000-0003-4884-108X</a><br> Paul M. Gignac, University of Arizona, <a href="https://orcid.org/0000-0001-9181-3258">https://orcid.org/0000-0001-9181-3258</a><br> Amy Schuler, Cary Institute of Ecosystem Studies, <a href="https://orcid.org/0000-0002-2459-2413">https://orcid.org/0000-0002-2459-2413</a><br> Neggin Keshavarzian, Princeton University, <a href="https://orcid.org/0000-0001-6753-1226">https://orcid.org/0000-0001-6753-1226</a> |

# Objectives and Vocabulary

## Learning Objectives:

- Understand the steps of the DCN CURATED workflow.
- Apply the CURATED workflow to a real-world image dataset
- Through reflection and discussion, evaluate the CURATED
activities proposed in the workshop against those proposed by an
experienced curator

## Terms to Know (organized alphabetically):

- Data Curation Primers: Data curation primers are <a
href="https://datacurationnetwork.org/outputs/data-curation-primers/">peer-reviewed,
living documents</a> that detail a specific subject, disciplinary
area or curation task and that can be used as a reference to curate
research data.
- Deep Blue Data: a repository offered by the University
of Michigan Library that provides access and preservation services for
digital research data that were developed or used in the support of
research activities at U-M.
- Lossless file format: File compression in which file
size is reduced without losing data or quality from the original file.
When a lossless file is uncompressed, it is identical to the original
file before compression (e.g., PNG, TIFF, RAW files).
- Lossy file format: File compression in which file size
is reduced by permanently eliminating some amount of information,
especially redundant or less important data. This process results in
some loss of quality compared to the original file (e.g., JPEG
files)
- Pixel: The smallest unit of a 2D image, representing
brightness and/or color. The width and length of a pixel may correspond
to physical measurements of distance.
- Raster: A type of digital image (e.g., in PNG or TIFF
file format) that is composed of a discrete grid of pixels corresponding
to specific picture elements. Raster images have inherent limitations
when it comes to size scaling due to their pixel-based nature (in
contrast to vector.)
- Scientific Images: Visual representations of recorded
factual material, 1) composed of a finite number of elements with a
particular location and value, and 2) commonly accepted in the
scientific community as of sufficient quality to validate and replicate
research findings.
- Small: A peer-reviewed and primary research-focused
scientific journal addressing nano/micro-scale materials and phenomena.
With a 2021 Journal Impact Factor of 15, Small continues to be
among the top multidisciplinary journals covering a broad spectrum of
topics at the nano- and microscale at the interface of materials
science, chemistry, physics, engineering, medicine, and
biology.
- Vector: A type of digital image (e.g.,in EPS file
format) that is composed of mathematical equations used to represent
picture elements. The equations define discrete paths that create simple
geometric shapes (e.g., points, lines, curves, circles, and polygons)
and complex images. Vector images can be size scaled without losing
quality.
- Voxel: The smallest unit of a 3D volume, representing
brightness and/or color (i.e., a “3D pixel”). The width, length, and
depth of a voxel may correspond to physical measurements of
distance.
- Z-stack: A series of 2D images, each with X and Y
dimensions, aligned along a third axis of depth (the Z-axis). This
alignment forms a coherent sequence, creating a 3D representation by
adding volume information to traditionally flat X and Y axes.

See <a
href="https://www.pearson.com/en-gb/subject-catalog/p/digital-image-processing-global-edition/P200000004313/9781292223070">this
resource</a> for further scientific imaging terminology and
definitions.


# Dataset(s) for Lesson 

Required Tools/Software:

- Web browser
- text editing software
- ImageJ (a.k.a., FIJI)


- Instructions can be found in “Pre-Work” document

## Dataset Citations:

Moniri, S., Bale, H., Volkenandt, T., Wang, Y., Gao, J.,
Lu, T., Sun, K., Shahani, A. J. (2020). Dataset for 'Multi‑Step
Crystallization of Self‑Organized Spiral Eutectics' [Data set],
University of Michigan - Deep Blue Data. <a
href="https://doi.org/10.7302/day1-6d63">https://doi.org/10.7302/day1-6d63</a>


# Outline and Content 


- Introduction
	- Aims
	- Curator Log
	- What are scientific images?
	- Software Roundup & Get ImageJ Running
- Check
	- Introduce Check Worksheet
	- Activity: file format, general requirements
- Understand
	- Introduction to Understand step
	- Think-pair-share activity
		- Review of questions needed to understand data
			- Share out 1 : Did the data pass the Check step?
		- Digging Deeper
			- Share out 2: What didn’t you understand about the dataset?
- Request
	- Introduce the Request step
	- Example Request step email template
	- Request step Activity
		- Group role-play activity & report back;
		- Group AI activity & report back
- Augment
	- Introduction
	- What is metadata?
	- Considerations
- Transformation
	- Introduction with example
	- Transformation activity & group discussion
- Evaluate
	- Introduction to FAIR & CARE
	- Evaluate exercise
- Document
	- Group Discussion about Curator Log contents
- Review and Summary
- Questions


## Introduction 
Mode(s): Lecture <br>
Estimated time: 15 minutes<br><br>
Describe aims of the workshop, <br>introduce the curator log, define and
describe what scientific images are and review important software to
view and manipulate images.


## Check Step
Mode(s): Lecture, activity and small group
discussion<br>
Estimated time: 30 minutes<br><br>
Checking the data is the first step to determining if what
has been submitted is curatable.<br><br>
Lecture will introduce the steps to check files, then there will be a
short activity and small group discussion about checking file format -
(e.g., corrupt file, open-access file), and comparing different required
fields for generalist vs. specialized repositories. Is the data
appropriate to be shared?<br><br>
Please use the worksheet <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/1-Check_worksheet.pdf">here</a>
to assist with the activity.


## Understand Step
Mode(s): Lecture, small group
discussion <br>
Estimated time: 20 minutes <br><br>
Understanding the data is an important step to ensure that
the data content, context, and quality can be described accurately and
precisely for someone else. Small group discussions will be used to
determine what information is missing from the Deep Blue Data entry.
Each participant will come up with a list of up to five questions that
they have based on their attempt to understand the data. A question may
be as straightforward as, “how are .CTF files read?”. Alternatively, a
question may be as complex as, “how do the included .PNG files relate to
each other spatially, if at all?”. <br><br>

Group members will compile a list of their questions, and then divide
up the list to search for answers. Answers should be referenced, and
answers that cannot be found should be tallied for the Request step. <br><br>
Please use the worksheet <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/2-Understand_worksheet.pdf">here</a>
to assist with the activity.
Please save the list of questions and answers for the
Documentation.

## Request Step
Mode(s): Lecture, activity and small group
discussion<br>
Estimated time: 20-25 minutes <br><br>
Requesting additional information is an important mechanism
to ensure that the data will pass additional quality checks. <br><br>
Consider using a <a
href="https://www.lucidmeetings.com/glossary/plus-delta">plus-delta</a>
model of requesting information by describing what content was helpful,
and requesting additional information that enhances the dataset’s
accessibility. <br><br>
A useful approach for this step is to refer to which questions from
the Understand step either 1) cannot be answered with
documentation available, and/or 2) require additional confirmation to
ensure the specific, relevant, and complete. These constitute targets
for Request. The group members should now draft a communication
with the data submitter requesting missing information identified
previously, using the Request more information letter (a completed
example/template letter <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/3-Request_worksheet.pdf">here</a>).

## Augment Step
Mode(s): Lecture, discussion <br>
Estimated time: 15 minutes <br><br>
Augmenting the original dataset submitted is how incomplete
submissions become curatable. This step includes appreciating metadata
relevant to the submission. <br><br>
Small groups will examine the information gathered in the Understand
and Request steps of the CURATED workflow. Participants will parse these
for the “missing pieces” previously identified in the Understand step.
Working collaboratively, the participants of each group will determine
how and where to augment the dataset metadata and documentation to
include the missing elements. <br><br> 

Please use the worksheet <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/4-Augment_worksheet.pdf">here</a>
to assist with the activity.


## Transformation Step

Mode(s): Lecture, activity, small group
discussion <br>
Estimated time: 35 minutes <br><br>
Transforming data into widely accessible formats ensures
that the curated dataset can be maximally utilized. Lecture on
file-format transformation and transformation activity. Participants
will transform the image datasets, examine the changes made to the data,
and discuss the implications of the transformation for curation and data
sharing. <br><br>
In this step, consider the file formats in the dataset to make them
more interoperable, reusable, preservation friendly, and non-proprietary
when possible.[^1] <br><br>
Common TRANSFORM steps include:

- Identify specialized file formats and their restrictions (e.g.,
Is the software freely available? If so, link to it or archive it
alongside the data)
- Propose open source or more reusable formats when appropriate
(e.g., TIFF (uncompressed), JPEG2000 (lossless) (*.jp2), or PNG
(*.png))
- Retain original file formats

[^1]: See Cornell’s list of preservation format
recommendations: <a
href="http://guides.library.cornell.edu/ecommons/formats">http://guides.library.cornell.edu/ecommons/formats</a> <br>
Library of Congress - Sustainability of Digital Formats:
<a
href="https://www.loc.gov/preservation/digital/formats/content/still.shtml">https://www.loc.gov/preservation/digital/formats/content/still.shtml</a> <br>
Use the worksheets here for transformation activities:
Complete activity on your own: <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/5-Transform_worksheet.pdf">5-Transform_worksheet_no_results</a> <br>
Follow along: <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/5-Transform_worksheet.pdf">5-Transform_worksheet</a>


## Evaluate Step

Mode: Lecture, small group
discussion <br>
Estimated time: 15 minutes <br><br>
Evaluating the dataset ensures that space for
self-reflection on the augmented and transformed data submission is in
place. <br><br>
This will include a short overview of FAIR and CARE, then short
group/table discussions evaluating the spiral eutectics dataset
according to the FAIR checklist, and whether the CARE Principles apply
to this dataset (or may apply to scientific image data in general). <br><br>
Use <a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Scientific%20Images/Exercise%20Materials/Worksheets/6-Evaluate_discussion.pdf">6-Evaluate_discussion</a>
to guide your discussions.


## Document Step

Mode: Whole room discussion <br>
Estimated time: 10-15 minutes <br><br>
A whole room discussion about the documentation process. Please
revisit your curator log.

## Additional Resources 
### Bibliography

Bray, M.-A., S.M. Gustafsdottir, M.H. Rohban, S. Singh, V. Ljosa,
K.L. Sokolnicki, J.A. Bittker, et al. “A Dataset of Images and
Morphological Profiles of 30 000 Small-Molecule Treatments Using the
Cell Painting Assay.” GigaScience 6, no. 12 (2017): 1–5. <a
href="https://doi.org/10.1093/gigascience/giw014">https://doi.org/10.1093/gigascience/giw014</a>.


Driscoll, M.K., and A. Zaritsky. “Data Science in Cell Imaging.”
Journal of Cell Science 134, no. 7 (2021). <a
href="https://doi.org/10.1242/jcs.254292">https://doi.org/10.1242/jcs.254292</a>.


Goldberg, I.G., Allan, C., Burel, JM. et al. The Open Microscopy
Environment (OME) Data Model and XML file: open tools for informatics
and quantitative analysis in biological imaging. Genome Biol 6, R47
(2005). <a
href="https://doi.org/10.1186/gb-2005-6-5-r47">https://doi.org/10.1186/gb-2005-6-5-r47</a>


Gonzalez, R.C. and Woods, R.E. Digital Image Processing,
Global Edition, 4th Edition. Pearson (2018) <a
href="https://www.pearson.com/en-gb/subject-catalog/p/digital-image-processing-global-edition/P200000004313/9781292223070">https://www.pearson.com/en-gb/subject-catalog/p/digital-image-processing-global-edition/P200000004313/9781292223070</a>


Gonzalez-Beltran, A.N., P. Masuzzo, C. Ampe, G.-J. Bakker, S. Besson,
R.H. Eibl, P. Friedl, et al. “Community Standards for Open Cell
Migration Data.” GigaScience 9, no. 5 (2020). <a
href="https://doi.org/10.1093/gigascience/giaa041">https://doi.org/10.1093/gigascience/giaa041</a>.


Linkert, M., C.T. Rueden, C. Allan, J.-M. Burel, W. Moore, A.
Patterson, B. Loranger, et al. “Metadata Matters: Access to Image Data
in the Real World.” Journal of Cell Biology 189, no. 5 (2010):
777–82. <a
href="https://doi.org/10.1083/jcb.201004104">https://doi.org/10.1083/jcb.201004104</a>.


Marmo, C., T.M. Hare, S. Erard, M. Minin, F.-X. Pineau, A. Zinzi, B.
Cecconi, and A.P. Rossi. “FITS Format for Planetary Surfaces:
Definitions, Applications, and Best Practices.” Earth and Space
Science 5, no. 10 (2018): 640–51. <a
href="https://doi.org/10.1029/2018EA000388">https://doi.org/10.1029/2018EA000388</a>.


Pence, W.D., L. Chiappetti, C.G. Page, R.A. Shaw, and E. Stobie.
“Definition of the Flexible Image Transport System (FITS), Version 3.0.”
Astronomy and Astrophysics 524, no. 10 (2010). <a
href="https://doi.org/10.1051/0004-6361/201015362">https://doi.org/10.1051/0004-6361/201015362</a>.


Piovesan, A., V. Vancauwenberghe, T. Van De Looverbosch, P. Verboven,
and B. Nicolaï. “X-Ray Computed Tomography for 3D Plant Imaging.”
Trends in Plant Science 26, no. 11 (2021): 1171–85. <a
href="https://doi.org/10.1016/j.tplants.2021.07.010">https://doi.org/10.1016/j.tplants.2021.07.010</a>.


Sarkans, U., Chiu, W., Collinson, L. et al. REMBI:
Recommended Metadata for Biological Images—enabling reuse of microscopy
data in biology. Nat Methods 18, 1418–1422 (2021). <a
href="https://doi.org/10.1038/s41592-021-01166-8">https://doi.org/10.1038/s41592-021-01166-8</a>


Williams, E., J. Moore, S.W. Li, G. Rustici, A. Tarkowska, A.
Chessel, S. Leo, et al. “Image Data Resource: A Bioimage Data
Integration and Publication Platform.” Nature Methods 14, no. 8
(2017): 775–81. <a
href="https://doi.org/10.1038/nmeth.4326">https://doi.org/10.1038/nmeth.4326</a>.


Wilson, S.L., G.P. Way, W. Bittremieux, J.-P. Armache, M.A. Haendel,
and M.M. Hoffman. “Sharing Biological Data: Why, When, and How.”
FEBS Letters 595, no. 7 (2021): 847–63. <a
href="https://doi.org/10.1002/1873-3468.14067">https://doi.org/10.1002/1873-3468.14067</a>.


Zaritsky, A. “Sharing and Reusing Cell Image Data.” Molecular
Biology of the Cell 29, no. 11 (2018): 1274–80. <a
href="https://doi.org/10.1091/mbc.E17-10-0606">https://doi.org/10.1091/mbc.E17-10-0606</a>.

### Other Resources
<a
href="https://carpentries.org/blog/2023/01/dc-image-processing-stable-release/">Data
Carpentry: Image Processing with Python</a>

