# Data Curation Network Lesson Plan: Curating Simulation-based Research 


| Lesson Components | Lesson Description |
| ------------- | ------------- |
| Data Type | Simulation Data, Simulation Models, Simulation Workflows |
| Primary fields or areas of use  | <li>Oceanography and Atmospheric Sciences and Meteorology</li><li>Earth Sciences</li><li>Chemical Engineering</li><li>Astrophysics and Astronomy</li><li>Aerospace Engineering</li><li>Civil and Environmental Engineering</li><li>Physics</li><li>Chemistry</li><li>Climate</li> |
| Common file formats  | <li>netCDF</li><li>HDF, HDF5</li><li>MAT</li><li>.m</li><li>.dat</li><li>RData</li><li>Tabular (.csv &amp; .xls)</li><li>Text</li><li>Other binary formats</li> |
| Summary  | The curriculum covers a range of foundational background information about what simulation data is and the pieces that make up simulation datasets. The workshop looks at two simulation datasets throughout and a third dataset when focusing on the Transform step. The curriculum teaches learners to formulate high impact considerations that uncover traditional barriers to FAIR when curating simulation data. This curriculum leans to a high level overview of the workshop, the curriculum requires the slides for more detail. <br><br> This curriculum assumes some prior knowledge of CURATE(D) and exposure curating scientific data. The size of the two datasets are 403 MB and 2 GB and require the data to be downloaded onto a device such as Windows, OSX, or Linux. |
| Estimated time  | 2.5 hours |
| Related primers  | See published <a href="https://datacurationnetwork.org/outputs/data-curation-primers/">primers</a> <br><br> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Accessibility%20Data%20Curation%20Primer/accessibility-data-curation-primer.md">Accessibility Data Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/PDF%20Data%20Curation%20Primer/PDF-data-curation-primer.md">Acrobat PDF Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Column%20Binary%20Data%20Curation%20Primer/column-binary-data-curation-primer.md">Column Binary Data Curation Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md">Jupyter Notebooks Primer</a></li> <li><a href="https://deepblue.lib.umich.edu/handle/2027.42/154686">Matlab Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/MSAcess%20Data%20Curation%20Primer/MSAccessCopy2.md">Microsoft Access Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Excel%20Data%20Curation%20Primer/Excel%20Data%20Curation%20Primer.md">Microsoft Excel Primer</a></li> <li><a href="https://deepblue.lib.umich.edu/handle/2027.42/145724">netCDF Primer</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md">R Primer</a></li> |
| Link to Slides  | Slide Deck: <a href="https://docs.google.com/presentation/d/1QUE-AdhvZZFzDQhe3SGfrPBtmL-dex6mb06wMVYwBkg/edit?usp=sharing">Curating simulation-based research</a> |
| Date Created | July 2023 |
| Created By | L. Wynholds, UCLA, https://orcid.org/0000-0002-9066-9773<br>Heather Shimon, University of Wisconsin-Madison, https://orcid.org/0000-0002-4395-0132<br>Fernando Rios, University of Arizona, https://orcid.org/0000-0001-6262-3260<br> Girmaye Misgna, University of Pennsylvania<br> Wanda Marsolek, University of Minnesota, https://orcid.org/0000-0002-1771-3969 |


# Objectives and Vocabulary

Learning Objectives:
1. Participants will gain a basic understanding of simulation data
and simulation-based research for curation purposes
	- key characteristics/unique elements of simulation data
	- intro to simulation data models
	- examples of uses for simulation data
	- pointing to other DCN primers
	- overview of jargon/glossary

2. Participants will understand how to develop discussions with
researchers regarding their simulation data. Through guided interactions
with each other, participants will develop dataset specific approaches
to establishing key questions necessary for interacting with researchers
and curating simulation data.
	- key questions from CURATED perspective (e.g. how to document)
	- common challenges related to simulation data
	- helpful materials for CURATED activities (e.g. NCAR rubric)
	- what to preserve
	- ethical considerations
	- accessibility considerations
	- equity considerations
3. Participants will work with example datasets to gain a better
understanding of common tools, methods and practices used to produce and
curate simulation data
	- methods
	- data models
	- file formats
	- licensing, data use agreements


Glossary: <a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Simulations/Simulations_glossary.pdf">Terms to Know</a></td>

# Dataset(s) for Lesson 

Required Tools/Software:
- text editor
- PDF viewer
- spreadsheet program
- browser-based viewer for looking at simulation data formats, depends on dataset

## Dataset Citations:
Dataset A:

Yang, Huang; Waugh, Darryn W., 2020, "Data associated with Yang et
al., 2020, Dependence of Atmospheric Transport into the Arctic on Extent
of the Hadley Cell", <a href="https://doi.org/10.7281/T1/AWJUGZ">https://doi.org/10.7281/T1/AWJUGZ</a>, Johns Hopkins Research Data Repository, V1

Dataset B:

Do, H. X., Smith, J. P., Fry, L. M., Gronewold, A. D. (2020). Monthly
water balance estimates for the Laurentian Great Lakes from 1950 to 2019
(v1.1) [Data set], University of Michigan - Deep Blue Data. <a
href="https://doi.org/10.7302/tx97-nn12">https://doi.org/10.7302/tx97-nn12</a>

Dataset C:

Horna Munoz, Daniel; Constantinescu, George; Rhoads, Bruce ; Lewis,
Quinn; Sukhodolov, Alexander (2020): Confluence Density Effects
Simulation Database. University of Illinois at Urbana-Champaign. <a
href="https://doi.org/10.13012/B2IDB-6257171_V1">https://doi.org/10.13012/B2IDB-6257171_V1</a></td>



<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="outlineoverview-of-simulation-data">Outline/Overview of
Simulation Data</h2></td>
</tr>
<tr class="even">
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="media/image1.png" style="width:3.02083in;height:2.70833in"
alt="Decorative image to show process of simulation data for curation purposes. Input data (initial conditions) -&gt; Code (model) -&gt;simulation output" /></td>
<td><ul>
<li>Simulations/models tend to follow a linear workflow process, e.g.
a set of initial data, a body of code processing the data and a
resulting output
<ul>
<li><blockquote>
input data -&gt; code -&gt; output data
</blockquote></li>
</ul></li>
<li>All three elements need to be adequately described for curation
purposes
<ul>
<li><blockquote>
the data archive might include only portions of the above three
elements
</blockquote></li>
</ul></li>
<li>Simulation models share many similarities to AI models. The
former tend to be driven by mathematical models while the latter
resemble a black box where the model is not known exactly and is driven
by the input data (via training)</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="outline-and-content">Outline and Content</h2></td>
</tr>
<tr class="even">
<td><h3 id="introduction">Introduction </h3></td>
</tr>
<tr class="odd">
<td>Mode(s): Lecture
Estimated time: 20-25
minutes</td>
</tr>
<tr class="even">
<td>Lesson intro
<ul>
<li>Introduce goals/objectives</li>
<li>Scope
<ul>
<li>focus on conceptual aspects of curation</li>
<li>no focus on specific file formats. Refer to other
primers.</li>
<li>no AI/ML</li>
</ul></li>
<li>Activity 1 (background questions)</li>
</ul>
What is special about curating simulation models and data?
<ul>
<li>Key points of <a
href="https://www.frontiersin.org/articles/10.3389/fclim.2021.763420/full">Open
Science Expectations for Simulation-Based Research by Mullendore,
Mayernik, and Shuster (2021)</a></li>
<li>Key characteristics/unique elements of simulation data</li>
<li>Simulation vs AI/ML</li>
<li>Mention that CURATED is more for explanatory reasons, in reality,
things happen non-linearly, steps might happen simultaneously</li>
</ul>
Simulation data and the CURATED curation model
<ul>
<li>Nothing special about the data themselves</li>
<li>Lean heavily on other primers for tools and guides</li>
<li>Especially code/software curation</li>
</ul>
Exercise: "What I Know," "What I Want to Know," <del>and "What I
Learned</del>. (KWL) KW mentimeter</td>
</tr>
<tr class="odd">
<td><h3 id="document-evaluate">Document &amp; Evaluate </h3></td>
</tr>
<tr class="even">
<td><h3
id="modes-lecture-download-curation-log-template">Mode(s):
Lecture, download curation log template </h3>
<h3 id="section"></h3>
<h3 id="estimated-time-5-10-minutes">Estimated time:
5-10 minutes</h3></td>
</tr>
<tr class="odd">
<td>Lecture:
Introduce Document and Evaluate steps, steps are iterative and
curation is not linear.
Download the Curation Log template and use it throughout the rest of
the workshop for the document step.
Evaluation will be done throughout the curation process, in each step
rather than an end step, but also at the end. Constantly thinking about
the datasets’ FAIRness, can it be made more FAIR, and how.</td>
</tr>
<tr class="even">
<td><h3 id="check-step">Check step </h3></td>
</tr>
<tr class="odd">
<td><h3
id="modes-lecture-independent-exercise">Mode(s):
Lecture, independent exercise </h3>
<h3 id="section-1"></h3>
<h3 id="estimated-time-30-minutes">Estimated time:
30 minutes</h3></td>
</tr>
<tr class="even">
<td>Lecture:
CURATE(D) CHECK step revolves around inventorying and reviewing the
contents of the dataset and verifying that it is appropriate for the
repository. This often includes:
<ul>
<li>Review to ensure data is in scope for the repository</li>
<li>Inventory the contents of the data files (e.g., open and sample
the files or code)</li>
<li>Verify all metadata provided by the researcher; check available
documentation</li>
</ul>
Simulation data tends to be the result of interactions between
models, datasets and code. The check step needs to document how the data
was produced, including documenting the details of the code and data
used to produce the dataset.
When checking simulation data pay special attention to checking
for:
<ul>
<li>code used to produce the dataset
<ul>
<li>is the code used to produce the dataset included in the dataset
packages?</li>
<li>is the code archived elsewhere?</li>
<li>is the code part of another project?</li>
<li>is the version of the code documented?</li>
<li>is adequate documentation of code runs included in the metadata?
e.g. version of coding language, details of computers used to run code,
date of code runs, etc.</li>
</ul></li>
<li>documentation of related materials
<ul>
<li>is the production of the model, code, programming languages,
initial data, data processing, metadata, etc already documented
elsewhere?</li>
</ul></li>
<li>documentation of data production
<ul>
<li>was there initial or calibration data used? Is it documented?
included in the dataset? published elsewhere?</li>
<li>what formats or metadata standards were used?</li>
<li>is the initial data derived from other datasets? if so, is it
already documented elsewhere?</li>
</ul></li>
<li>references to data formats/metadata standards/code
used/programming languages used
<ul>
<li>are the references to formats, metadata standards, code, etc
documented in such as manner as to be readily accessible for indexing
and/or machine readable?</li>
</ul></li>
<li>related publications
<ul>
<li>are the references to related publications documented adequately
to be readily accessible for indexing?</li>
<li>are any of the related publications required to understand the
data? if so, is that adequately represented in the
metadata/documentation?</li>
</ul></li>
</ul>
In addition to the standard Check steps
<ul>
<li>How to determine whether a dataset might be simulation
data/code?
<ul>
<li>data clues</li>
<li>software clues</li>
<li>keywords to look for</li>
</ul></li>
<li>Look for ethics issues around the code, initial data, model, etc,
especially around human subjects data, sensitive species information, or
other issues that may be politically contentious but not necessarily
sensitive (e.g. climate modeling)
<ul>
<li>ethics of access to publications (e.g. publication being behind a
paywall)</li>
</ul></li>
<li>Sample data and parameters
<ul>
<li>Are these included or available elsewhere (other repositories,
paper)</li>
</ul></li>
<li>Relevant primers to refer to
<ul>
<li>Code</li>
<li>netCDF</li>
<li></li>
</ul></li>
<li>Short exercise - 10 min
<ul>
<li>Given a dataset, determine whether it is simulation data or
not</li>
<li>Do the necessary files appear to be there?</li>
<li>Sample dataset: <a
href="https://doi.org/10.7281/T1/AWJUGZ">https://doi.org/10.7281/T1/AWJUGZ</a></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="understand-step">Understand Step</h3></td>
</tr>
<tr class="even">
<td>Mode(s): Lecture
Estimated time: 25 minutes</td>
</tr>
<tr class="odd">
<td>Lecture (25 minutes)
CURATE(D) Understand Step
The Understand step is the deeper dive into the data/code and how it
makes sense together.
<ul>
<li>After inventorying and reviewing the contents, the Understand
step is a closer examination of:
<ul>
<li>what they are</li>
<li>how they interrelate</li>
<li>what information is needed for reuse</li>
</ul></li>
<li>Check and Understand steps generate the information needed for
the Request step.</li>
</ul>
Understand step often includes
From the general CURATED model, we are going beyond checking, we are
trying to understand how the files fit together, if someone with similar
disciplinary knowledge would be able to make sense of the collection,
and pulling from the Evaluate step to make sure that files open and meet
ethical requirements for sharing.
<ul>
<li>Examining for quality assurance and usability
issues</li>
<li>Assessing for ethical issues including sensitive
data, consent, risk to persons/places, licensing/permissions,
accessibility, etc. (see “Checking for Ethical Concerns” slide)</li>
<li>Determining if the documentation is sufficient
for peer researchers to understand and reuse the contents</li>
<li>Understanding how the files relate to each
other</li>
</ul>
Understand step: Simulations specifically
For simulation data, we are considering a sequential workflow with
consistent naming conventions. This means looking for missing files in a
sequence and checking that file names follow the naming convention in
order to understand how they relate to each other.
Focus on how the files relate to each other
<ul>
<li>Simulation data can consist of sequential files - check for
missing files in a sequence</li>
<li>Often, experiments are repeated and datasets will contain
multiple similar folders and files
<ul>
<li>Check that naming conventions are consistent</li>
<li>Also keep in mind that a standard duplicate file check will
usually reveal multiple identical files ‒ for simulation data, this is
often ok, since only small things may change between runs, and there can
be repeated files due to multiple runs of the model</li>
</ul></li>
</ul>
<ul>
<li>Helpful tools</li>
<li><blockquote>
Directory exploration
</blockquote>
<ul>
<li><blockquote>
<a href="https://windirstat.net/index.html">WinDirStat</a>
(Windows Directory Statistics), <a
href="https://diskanalyzer.com/">WizTree</a> (Windows)
</blockquote></li>
<li><blockquote>
<a href="https://wiki.gnome.org/Apps/DiskUsageAnalyzer">Disk Usage
Analyzer/baobab</a> (Linux, Mac, Windows/WSL)
</blockquote></li>
</ul></li>
<li><blockquote>
Duplicate checkers
</blockquote>
<ul>
<li><blockquote>
<a
href="https://apps.microsoft.com/detail/9P8TBNHH1MS9?hl=en-us&amp;gl=US">Duplicate
File Finder</a> (Windows)
</blockquote></li>
<li><blockquote>
<a
href="https://github.com/adrianlopezroche/fdupes">fdupes</a>
(Linux)
</blockquote></li>
</ul></li>
<li>Make sure it’s clear which outputs correspond to which
inputs</li>
<li>Reference the publication if it is available. This can help you
understand the model and how the files work together.</li>
</ul>
Understand: DCN primers for data formats
The example that we looked at had familiar data formats, but
simulation data can be in many formats. Use the data curation primers
when working with formats that you are unfamiliar with.
<ul>
<li>Simulation data can be in many formats</li>
<li><a
href="https://datacurationnetwork.org/outputs/data-curation-primers/">Data
curation primers</a> useful when working with simulation data
<ul>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Accessibility%20Data%20Curation%20Primer/accessibility-data-curation-primer.md">Accessibility
Data Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/PDF%20Data%20Curation%20Primer/PDF-data-curation-primer.md">Acrobat
PDF Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Column%20Binary%20Data%20Curation%20Primer/column-binary-data-curation-primer.md">Column
Binary Data Curation Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md">Jupyter
Notebooks Primer</a></li>
<li><a
href="https://deepblue.lib.umich.edu/handle/2027.42/154686">Matlab
Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/MSAcess%20Data%20Curation%20Primer/MSAccessCopy2.md">Microsoft
Access Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Excel%20Data%20Curation%20Primer/Excel%20Data%20Curation%20Primer.md">Microsoft
Excel Primer</a></li>
<li><a
href="https://deepblue.lib.umich.edu/handle/2027.42/145724">netCDF
Primer</a></li>
<li><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md">R
Primer</a></li>
</ul></li>
</ul>
Which parts are needed? (Review from introduction
slides)
Simulation data can consist of many files -- and it might not be
useful or possible to keep everything. That is why it is so important to
remember that simulation data are tools for knowledge production, not
data production; and that “knowledge production research should preserve
minimal output in repositories.” (See “Characteristics of simulation
data” introduction slide)
What we DO need to preserve are the inputs (initial conditions),
code/model, and outputs - depending on the project, could be available
through another provider. (See “Common elements of simulation models”
introduction slide)
And provide documentation of how it all works together.
One of the important parts of the Understand step is figuring out
which parts of the dataset and model need to be curated to support
reproducibility and knowledge production purposes. In some cases, the
curator and researcher may need to archive the input and code, but not
keep the output. In other cases, the code may be archived elsewhere and
the input described in detail in a publication. Each dataset is likely
to vary in which elements are critical, which is why the Understand step
is so important for simulation datasets.
Knowledge production vs data production
<ul>
<li>“... primary goal of most projects involving computer simulations
is to increase scientific knowledge and the simulations are used as a
tool to that end.”</li>
<li>“... we are producing far more simulation output than can be
reasonably stored in repositories. Knowledge production research should
preserve minimal output in repositories.” Mullendore et al.
(2021)</li>
</ul>
Components to preserve and share (this varies)
<ul>
<li>input data: initial conditions, calibration files, parameter
values</li>
<li>code/model: preprocessing, configuration, post
processing</li>
<li>outputs: depends on the simulation</li>
<li>documentation</li>
</ul>
What do these things look like?
Let’s look at Example Dataset B to see what common elements of
simulation models can look like.
Example Dataset B
Do, H. X., Smith, J. P., Fry, L. M., Gronewold, A. D. (2020). Monthly
water balance estimates for the Laurentian Great Lakes from 1950 to 2019
(v1.1) [Data set], University of Michigan - Deep Blue Data. <a
href="https://doi.org/10.7302/tx97-nn12">https://doi.org/10.7302/tx97-nn12</a>
From the files list, we can see that they include the inputs,
model/source code, and outputs.
[Show unzipped files]
<ul>
<li>Documentation, inputs, model/source code, and outputs</li>
<li>The README gives context with an overview, software
specification, variable definitions, and more
<ul>
<li>“This data set contains new estimates of the Great Lakes water
balance together with the L2SWBM source code and inputs synthesized for
this project…”</li>
</ul></li>
<li>Input files are Excel csv files</li>
<li>The source code/model R files are organized in run order and
include a config_README</li>
<li>Output files are pdfs and Excel csv</li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="request-step">Request Step</h3></td>
</tr>
<tr class="odd">
<td><h3
id="modes-lecture-small-group-activity">Mode(s):
Lecture, small group activity</h3>
<h3 id="section-2"></h3>
<h3 id="estimated-time-20-minutes">Estimated time:
20 minutes</h3></td>
</tr>
<tr class="even">
<td>Lecture (5 minutes)
CURATE(D) Request Step
The Request step is your opportunity to discuss the dataset with the
researcher. Pull the questions that have arisen from the Check and
Understand steps. This can include questions about the dataset
components to share, inconsistencies in the data, unclear run sequence,
missing files, bad naming conventions, sensitive data, etc.). Record
your questions for the researcher in your curator log.
<ul>
<li>Data appraisal conversations with researchers
<ul>
<li>Conversations about the dataset</li>
<li>Pull from the Check and Understand steps</li>
<li>Arrive at a shared understanding of the curation process with the
researcher (good for future conversations!)</li>
</ul></li>
</ul>
<ul>
<li>Record all questions/concerns (ethics, missing files, excessive
output files, bad naming conventions, etc.) in your Curator Log
📝</li>
</ul>
EarthCube rubric
If you are unsure about what output data to preserve, a tool for
conversations with researchers is the EarthCube rubric. Review it to
develop an understanding of the researcher perspective, identify
questions for researchers, and see examples of use cases for how much
data to preserve
<ul>
<li><a
href="https://zoidy.shinyapps.io/ModelDataRubric/">EarthCube
rubric</a> tool to:
<ul>
<li>Understand researcher perspective</li>
<li>Identify questions for researchers 📝</li>
<li>Determine the <a
href="https://modeldatarcn.github.io/rubrics-worksheets/Rubric-Instructions-and-Use-Cases.pdf">Use
Case</a> for output data to preserve
<ul>
<li>Use Case 1: “Preserve Few Simulation Workflow Outputs”</li>
<li>Use Case 2: “Preserve Selected Simulation Workflow
Outputs”</li>
<li>Use Case 3: “Preserve the Majority of Simulation Workflow
Outputs”</li>
</ul></li>
</ul></li>
</ul>
Role playing activity (15 minutes)
<ul>
<li>In groups of 4-6 people:
<ul>
<li>Open the <a
href="https://deepblue.lib.umich.edu/data/concern/file_sets/d504rk54x">README
file</a> from Example Dataset B and review it. Pay particular
attention to the “Research Overview” and the list of files under “Files
Contained Here.”</li>
<li>In your group, decide who will act as the researcher depositing
the output data, and who will act as the data curator receiving the data
files.</li>
</ul></li>
<li>Researchers work together and data curators work together. Open
the <a href="https://zoidy.shinyapps.io/ModelDataRubric/">EarthCube
rubric</a> and answer the questions as best you can with the <a
href="https://deepblue.lib.umich.edu/data/concern/data_sets/sb3978457#items_display">Example
Dataset B</a> in mind. Answer the questions as you would in your
role as the researcher or data curator.
<ul>
<li>You can use the file list in the README file, and/or download the
files to explore them further.</li>
<li>Note which questions are easier or more difficult for you to
answer in the role that you are in.</li>
<li>Discuss what questions you would ask the other role (researcher
or data curator).</li>
</ul></li>
<li>After completing the rubric, researchers and data curators
discuss together:
<ul>
<li>Did you arrive at the same Use Case?</li>
<li>What questions were easy or difficult to answer?</li>
<li>What questions do you have for each other?</li>
</ul></li>
<li>If time, discuss as a large group and see if the small groups had
similar experiences.</li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="augment-step">Augment Step</h3></td>
</tr>
<tr class="even">
<td>Mode(s): Lecture and large group
discussion
Estimated time: 10
minutes</td>
</tr>
<tr class="odd">
<td><ul>
<li>Metadata
<ul>
<li>Discipline standards
<ul>
<li>resources</li>
</ul></li>
<li>Improve findability, accessibility, and documentation
<ul>
<li>Cautionary tale (things that get changed/edited may need to be
changed throughout the dataset package)</li>
</ul></li>
</ul></li>
<li>Ethical Considerations
<ul>
<li>bibliographic information reflects correct author
attribution</li>
<li>licenses</li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="transformation-step">Transformation Step </h3></td>
</tr>
<tr class="odd">
<td>Mode(s): Lecture, independent
exercise
Estimated time: 30
minutes</td>
</tr>
<tr class="even">
<td>When dealing with simulation data, it is often necessary to
transform the data into file formats and standards that ensure
<mark>sharing, long-term access, preservation, and</mark>
interoperability across different tools and systems.
Discussion and Important considerations:
<ul>
<li>Understand, Check, and Augment steps lay the foundation for
actions to take in the Transform step.</li>
<li>Look for opportunities to transform in all the common elements of
simulation data (input, code, output, and documentation). However, the
most common and less risky transformation is in the output data and
documentation. There is a high risk of making mistakes, breaking the
workflow, or data corruption in attempting to transform the input and
code. For code/software suggestions can be made for open source
alternatives.</li>
<li>Simulation data formats can often be specific to particular
software or model structures varying across several disciplines,
complicating standardization efforts and contributing to the lack of a
clear archival standard. This makes selection of preservations formats
for simulation data challenging.</li>
<li>Transforming files to open formats can simplify access and
preserve data, but could also introduce subtle errors or loss of data
during transformation between file formats.</li>
<li>Considerations for transformation include complexity, effort
required, and actual improvement in accessibility.</li>
<li>All being equal, the preference should be for open file formats
when presented with a choice between proprietary and open file formats.
Otherwise, following the recommended file format statement of the
Library of Congress for Geospatial data, "preserving the most complete
data, even if proprietary, with a preference for native formats" also
works in the case of simulation data.</li>
<li>It is important to involve the researcher in the transformation
process to ensure data integrity and consider the best transformation
approach.</li>
<li>In most cases, It is advisable to let the researcher, who is the
most familiar with the data, perform the transformation themselves. This
helps reduce the risk of inadvertently altering important aspects of the
data.</li>
<li>Prioritize elements crucial for data submission and reuse when
deciding on transformation.</li>
<li>Also refer to other primers such as the geospatial data primer
and simulation code primer for specific recommendations to transforming
data.</li>
</ul>
Some commonly used simulation platforms/software:
<ul>
<li>OpenFOAM: <a
href="https://openfoam.org/">https://openfoam.org/</a></li>
<li>GNU Octave: <a
href="https://octave.org/">https://octave.org/</a></li>
<li>MATLAB: <a
href="https://www.mathworks.com/products/matlab.html">https://www.mathworks.com/products/matlab.html</a></li>
</ul>
Some common simulation data visualization &amp; transformation
tools:
<ul>
<li>Paraview: <a
href="https://www.paraview.org/">https://www.paraview.org/</a></li>
<li>VisIt: <a
href="https://visit-dav.github.io/visit-website/about/">https://visit-dav.github.io/visit-website/about/</a></li>
</ul>
<ul>
<li>Some simulation software and frameworks (such as MATLAB) provide
built-in tools or plugins for converting simulation data into
standardized formats offering export capabilities to formats like CSV,
XML, or Excel, allowing users to transform simulation data into widely
compatible formats.</li>
<li>Custom Scripting and Programming: Using programming languages
like Python, R, or MATLAB, you can write scripts to read simulation data
in one format, perform necessary transformations, and output it in a
different format or standard. This approach offers flexibility and
control over the transformation process.</li>
<li>Data Wrangling and Data Integration Platforms: Data wrangling
tools like OpenRefine provide features for data cleaning,
transformation, and integration. These platforms offer functionalities
to convert simulation data into standardized formats, resolve
inconsistencies, and ensure compatibility with various systems and
tools.</li>
<li>Employing help from AI methods (eg. ChatGPT code interpreter,
co-pilot) to write scripts for custom transformation in a specific
language such as python or R.</li>
</ul>
Exercise &amp; example dataset: Demonstrate data
inspection, tool search, and transformation process to make them more
interoperable, reusable, preservation friendly, and non-proprietary.
<ul>
<li>Climate engineering NetCDF files produced with the climate model
CESM1(WACCM)
https://www.cesm.ucar.edu/working_groups/Whole-Atmosphere/.
<ul>
<li><a
href="https://cornell.app.box.com/s/h18flj5i5oerjlkixcckns7vsz1v1o6m">https://cornell.app.box.com/s/h18flj5i5oerjlkixcckns7vsz1v1o6m</a></li>
<li>Transform older NetCDF format to HDF5 or NetCDF4</li>
<li>Alternative data example: <a
href="https://databank.illinois.edu/datasets/IDB-0791318">https://databank.illinois.edu/datasets/IDB-0791318</a></li>
</ul></li>
<li>Confluence Density Effects Simulation Database: <a
href="https://databank.illinois.edu/datasets/IDB-6257171">https://databank.illinois.edu/datasets/IDB-6257171</a>
<ul>
<li>Transform the two xls files to csv and the docx documentation
file to .pdf format.</li>
<li>What is the .lay file? Can it be transformed into an open file
format? suggest alternative open format and conversion tools to the
proprietary tecplot, <a
href="https://www.tecplot.com/products/tecplot-360/">https://www.tecplot.com/products/tecplot-360/</a></li>
<li>Alternatives to Tecplot (CFD [computational fluid dynamics] 3d
simulation &amp; visualization software): Paraview (free and
open-source), OpenFOAM (free and open-source), VisIt (free and
open-source)</li>
<li>Evaluate: "Check that any transformations didn’t introduce
problems"</li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><h2 id="wrap-up">Wrap up</h2></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Mode(s): independent exercise/Group
exercise
Estimated time: 10 minutes</td>
</tr>
<tr class="even">
<td>Exercise: "What I Learned. (KWL) and “What is still muddy” L M
mentimeter</td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><h2 id="bibliography-resources">Bibliography &amp;
Resources</h2></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Ordered as referenced throughout lesson plan and slide deck
Interactive presentation software. Mentimeter. <a
href="https://www.mentimeter.com/">https://www.mentimeter.com/</a>
Mullendore, G. L., Mayernik, M. S., &amp; Schuster, D. C. (2021).
Open science expectations for simulation-based research. Frontiers in
Climate, 3, 763420. <a
href="https://doi.org/10.3389/fclim.2021.763420">https://doi.org/10.3389/fclim.2021.763420</a>
What About Model Data? Best Practices for Preservation and
Replicability. <a
href="https://zoidy.shinyapps.io/ModelDataRubric/">https://zoidy.shinyapps.io/ModelDataRubric/#</a>
<a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Simulations/Exercise%20Materials/Simulations_CuratorLog_Template.txt">CuratorLog.txt</a>
<a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Simulations/Exercise%20Materials/Simulations_CuratorLog_Template.txt">CuratorLog.google</a>
(make a copy for yourself)
<a
href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Simulations/Exercise%20Materials/Simulations_CuratorLog_Example_20230929.pdf">Sample
completed/redacted Curator Log</a>
<a
href="https://drive.google.com/file/d/1UEa_fIfWRPgKYf2wstQy9siF3gc4VxX1/view?usp=drive_link">Worksheet
for evaluating data quality</a>
Fair principles. GO FAIR. (2022, January 21). <a
href="https://www.go-fair.org/fair-principles/">https://www.go-fair.org/fair-principles/</a>
Global Indigenous Data Alliance. (n.d.). The CARE Principles for
Indigenous Data Governance. <a
href="https://www.gida-global.org/care">https://www.gida-global.org/care</a>
Microsoft . (2023, February 16). Fate: Fairness, accountability,
transparency &amp; ethics in Ai. Microsoft Research.
https://www.microsoft.com/en-us/research/theme/fate/overview/
Gebru, T., Morgenstern, J., Vecchione, B., Vaughan, J. W., Wallach,
H., Daumé III, H., &amp; Crawford, K. (2021, December 1). Datasheets for
datasets. arXiv.org. https://arxiv.org/abs/1803.09010
<mark>Yang, H., Waugh, D. W., Orbe, C., &amp; Chen, G. (2020).
Dependence of Atmospheric Transport Into the Arctic on the Meridional
Extent of the Hadley Cell. Geophysical Research Letters, 47(20). <a
href="https://doi.org/10.1029/2020gl090133">doi:
10.1029/2020gl090133</a></mark>
Do, H. X., Smith, J. P., Fry, L. M., &amp; Gronewold, A. D. (2020).
Seventy-year long record of monthly water balance estimates for Earth’s
largest lake system. Scientific Data, 7(1), 276. <a
href="https://doi.org/10.1038/s41597-020-00613-z">https://doi.org/10.1038/s41597-020-00613-z</a>
Gronewold, A. D., Smith, J. P., Read, L., &amp; Crooks, J. L. (2020).
Reconciling the water balance of large lake systems. Advances in Water
Resources, 103505. <a
href="https://doi.org/10.1016/j.advwatres.2020.103505">https://doi.org/10.1016/j.advwatres.2020.103505</a>
Metadata standards catalog. Metadata Standards Catalog. <a
href="https://rdamsc.bath.ac.uk/">https://rdamsc.bath.ac.uk/</a>
Tecplot. Tecplot 360. https://tecplot.com/products/tecplot-360/
kitware. Open-source, multi-platform data analysis and visualization
application. ParaView. <a
href="https://www.paraview.org/">https://www.paraview.org/</a>
OpenFOAM. <a
href="https://www.openfoam.com/">https://www.openfoam.com/</a>
University of Virginia Library. Data types &amp; file formats | UVA
Library. <a
href="https://library.virginia.edu/data/data-management/plan/format-types">https://library.virginia.edu/data/data-management/plan/format-types</a>
Library of Congress. Recommended Formats Statement – table of
contents | Resources (Preservation, Library of Congress). <a
href="https://www.loc.gov/preservation/resources/rfs/TOC.html">https://www.loc.gov/preservation/resources/rfs/TOC.html</a>
Cornell University Library. Ecommons: Cornell’s Digital
Repository: Recommended File Formats. <a
href="https://guides.library.cornell.edu/ecommons/formats">https://guides.library.cornell.edu/ecommons/formats</a></td>
</tr>
</tbody>
</table>