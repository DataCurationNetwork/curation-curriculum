# <a name="_heading=h.w9klu5phc851"></a>Data Curation Network Lesson Plan: 
# <a name="_heading=h.iwfwnp9t11tx"></a>Curating Code

<table>
<tr><th colspan="2" valign="top"><h2>Lesson Description</h2></th></tr>
<tr class="even">
<td><strong>Data Type</strong></td>
<td>Software source code (e.g., Python, R, Matlab)</td>
</tr>
<tr class="odd">
<td><strong>Primary fields or areas of use</strong></td>
<td>All</td>
</tr>
<tr class="even">
<td><strong>Summary</strong></td>
<td>This is a hands-on workshop introducing core conceptions of software
curation, including operating systems, programming languages,
dependencies, and documentation. Licensing, and project organization are
planned additions.</td>
</tr>
<tr class="odd">
<td><strong>Estimated time</strong></td>
<td><i>4 hours</i></td>
</tr>
<tr class="even">
<td><strong>Related primers</strong></td>
<td><p><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md"><em><u>Jupyter
Notebooks</u></em></a></p>
<p><a
href="https://hdl.handle.net/2027.42/154686"><em><u>Matlab</u></em></a></p>
<p><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/Python%20Primer/python.md"><em><u>Python</u></em></a></p>
<p><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md"><em><u>R</u></em></a></p>
<p><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/SAS%20Data%20Curation%20Primer/SAS-data-curation-primer.md"><em><u>SAS</u></em></a></p>
<p><a
href="https://github.com/DataCurationNetwork/data-primers/blob/master/SPSS%20Data%20Curation%20Primer/SPSS-data-curation-primer.md"><em><u>SPSS</u></em></a></p></td>
</tr>
<tr class="odd">
<td><strong>Link to Slides</strong></td>
<td><a href="https://docs.google.com/presentation/d/1NmwxppuUjVMmBYGwZJW1dU1wIByAFmKw0lGCeCfk0Fk/edit?usp=sharing">Code Lecture Slides</a></td>
</tr>
<tr class="even">
<td><strong>Date created</strong></td>
<td>October 2023</td>
</tr>
<tr class="odd">
<td><strong>Created by</strong></td>
<td><p>Talya Cooper, New York University, <a
href="https://orcid.org/0000-0003-4241-6330"><u>https://orcid.org/0000-0003-4241-6330</u></a></p>
<p>Greg Janée, University of California at Santa Barbara, <a
href="https://orcid.org/0000-0001-8785-0021"><u>https://orcid.org/0000-0001-8785-0021</u></a></p>
<p>Kay P Maye, Tulane University, <a
href="https://orcid.org/0000-0001-8615-1616"><u>https://orcid.org/0000-0001-8615-1616</u></a></p>
<p>Nick Ruhs, Florida State University, <a
href="https://orcid.org/0000-0002-3311-2661"><u>https://orcid.org/0000-0002-3311-2661</u></a></p>
<p>Seth Erickson, University of California at Santa Barbara, <a
href="https://orcid.org/0000-0002-5570-7201"><u>https://orcid.org/0000-0002-5570-7201</u></a></p></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="objectives-and-vocabulary">Objectives and
Vocabulary</h2></td>
</tr>
<tr class="even">
<td><p><strong>Learning Outcomes:</strong></p>
<p>By the end of this workshop, learners should be able to …</p>
<ul>
<li><p>Identify and explain real-world examples of how differences
between computing environments lead to reproducibility
problems.</p></li>
<li><p>Navigate significant differences between major operating systems
and understand how they affect the reusability of software</p></li>
<li><p>Identify several common programming languages used in research
computing and the file types and tools associated with each.</p></li>
<li><p>Identify and document dependencies used in research software for
common programming languages.</p></li>
<li><p>Identify and improve different types of documentation associated
with source code and research software.</p></li>
<li><p>Describe differences between software licenses and non-software
licenses, and differences between different kinds of open source
software licenses.</p></li>
<li><p>Implement commonly used project organization strategies used in
the research community.</p></li>
</ul>
<p><strong>Key Terms:</strong></p>
<ul>
<li><p><strong>Source Code</strong> - plain text, written in a
programming language, that can be run on a computer using an interpreter
or compiled into runnable machine code by a compiler.</p></li>
<li><p><strong>Operating System</strong>: system software that manages
computer hardware and software resources, and provides common services
for computer programs.</p></li>
<li><p><strong>File</strong>: a unit of stored data or information that
is managed by an operating system and uniquely identified by a “path”
(the file’s location within a hierarchical file system).</p></li>
<li><p><strong>Programming Language:</strong> a language used to develop
software programs, scripts, or other sets of instructions for a computer
to execute</p></li>
<li><p><strong>Software Dependency:</strong> Anything that a piece of
software relies on to function correctly, that is external to the
software itself.</p></li>
<li><p><strong>Documentation / README</strong>: Documentation written by
software authors or curators, primarily for the purpose of facilitating
the software’s reuse.</p></li>
<li><p><strong>Integrated Development Environment</strong> (IDE):
Software that facilitates writing and debugging software source
code.</p></li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="datasets-for-lesson">Dataset(s) for Lesson</h2></td>
</tr>
<tr class="even">
<td><p><strong>Required Tools/Software:</strong></p>
<p>We recommend using a source code editor (Visual Studio Code or
Sublime) to view example files, but this is not required.</p>
<p><strong>Dataset Citations:</strong></p>
<p>Bump, Joseph K; Beyer, Dean; O'Neil, Shawn. (2019). Code, data, and
metadata document for the manuscript: Territorial landscapes:
incorporating density-dependence into wolf resource selection study
designs. Retrieved from the Data Repository for the University of
Minnesota, <a
href="https://doi.org/10.13020/s40h-fv72"><u>https://doi.org/10.13020/s40h-fv72</u></a>.</p>
<p>Heuschele, Deborah; Furuta, Daniel; Smith, Kevin; Marchetto, Peter.
(2022). Data and analysis code for "Capturing High Resolution Plant
Movement in the Field". Retrieved from the Data Repository for the
University of Minnesota, <a
href="https://doi.org/10.13020/7e6x-8f36"><u>https://doi.org/10.13020/7e6x-8f36</u></a>.</p></td>
</tr>
<tr class="odd">
<td></td>
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
<td></td>
</tr>
<tr class="odd">
<td><h3 id="introduction">Introduction</h3></td>
</tr>
<tr class="even">
<td><p><strong>Mode(s):</strong> <em>Presentation, Case Study</em></p>
<p><strong>Estimated time<em>: </em></strong><em>10 mins</em></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overview</strong>:</p>
<p>We start the workshops with a short case study (“Willoughby-Hoye
Scripts”) illustrating the challenge of reproducibility and the
importance of software curation. Core concepts that structure the rest
of the workshop are also introduced: computing platforms, programming
languages, dependencies, documentation, licensing, and project
organization.</p>
<p><strong>Learning Outcomes</strong>:</p>
<ul>
<li><p>Identify and explain a real-world example of how differences
between computing environments can lead to non-reproducible
code.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-1-computing-platforms">Module 1: Computing
Platforms</h3></td>
</tr>
<tr class="odd">
<td><p><strong>Mode(s):</strong> <em>Lecture, Demonstration</em></p>
<p><strong>Estimated time:</strong> 30 mins</p></td>
</tr>
<tr class="even">
<td><p><strong>Overview:</strong></p>
<p>This module will introduce some of the basic characteristics of
computing platforms, and how incompatibilities across platforms can
cause programs to not run at all, to operate incorrectly, or to produce
different output.</p>
<p><strong>Learning Outcomes:</strong></p>
<ul>
<li><p>Understand elements of computing platforms</p></li>
<li><p>Understand differences between compiled and interpreted
languages</p></li>
<li><p>Understand obstacles to reproducibility</p></li>
<li><p>Understand implications for curation</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="module-2-programming-languages">Module 2: Programming
Languages</h3></td>
</tr>
<tr class="even">
<td><p><strong>Mode(s):</strong> <em>Lecture</em></p>
<p><strong>Estimated time<em>: </em></strong> <em>30 mins</em></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overview:</strong></p>
<p>This module will introduce the concept of a programming language and
will then discuss three common programming languages that are used by
researchers–Python, R, and MATLAB. Learners will become familiar with
the applicability of these three programming languages, as well as file
formats that are used by each language for program files or scripts.
They will also be introduced to integrated development environments and
how they are utilized with programming languages and software.</p>
<p><strong>Learning Outcomes:</strong></p>
<ul>
<li><p>Describe common programming languages used in academic research
and their applications</p></li>
<li><p>Identify key file types and extensions associated with MATLAB,
Python, and R</p></li>
<li><p>Introduce common Integrated Development Environments (IDE) and
Notebooks for these programming language</p></li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-3-dependencies">Module 3: Dependencies</h3></td>
</tr>
<tr class="odd">
<td><p><strong>Mode(s):</strong> <em>Lecture, Activity</em></p>
<p><strong>Estimated time<em>: </em></strong><em>30 mins</em></p></td>
</tr>
<tr class="even">
<td><p><strong>Overview:</strong></p>
<p>This module will discuss software dependencies: how researchers use
them and keep them up to date; how to observe their use in code in R,
Python, and MATLAB; and the potential problems they can pose for
reproducibility and curation. Learners will become familiar with the
idea of versioning and the concept of package managers. They will also
learn how to recommend that code creators document dependencies for
maximal reproducibility.</p>
<p><strong>Learning Outcomes:</strong></p>
<ul>
<li><p>Define “dependency” and learn why dependencies are used</p></li>
<li><p>Identify when dependencies are being used in code</p></li>
<li><p>Gain familiarity with package managers and versioning</p></li>
<li><p>Learn several ways to record dependencies–via README,
programmatically, and through the use of containerization</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="module-4-documentation"> Module 4: Documentation</h3></td>
</tr>
<tr class="even">
<td><p><strong>Mode(s):</strong> <em>Lecture, Small Group Discussion,
Individual Activity</em></p>
<p><strong>Estimated time<em>:</em></strong> <em>30 mins - 40
mins</em></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overview:</strong></p>
<p>This module introduces learners to methods for documenting research
software. Documentation helps researchers, curators, and users find,
access, and implement research software. Learners will be able to
identify how to use documentation to inform their curation practices and
how to offer edits to depositors.</p>
<p><strong>Learning Outcomes:</strong></p>
<ul>
<li><p>Identify types of research software documentation and how they
can be useful during the curation process</p></li>
<li><p>Make suggestions for research software documentation (README,
Commenting, Markdown, etc.)</p></li>
<li><p>Review and offer edits to README files/outlines for research
software</p></li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-5-licensing-not-covered-in-pilot-workshop">Module 5:
Licensing (not covered in pilot workshop)</h3></td>
</tr>
<tr class="odd">
<td><p><strong>Mode(s):</strong> <em>Lecture</em></p>
<p><strong>Estimated time<em>: </em></strong><em>30 mins</em></p></td>
</tr>
<tr class="even">
<td><p><strong>Overview:</strong></p>
<p>A license is legal permission for others to copy, modify, and share
your work. An open source software license is one that permits free
distribution of source code and the creation of derived works. We’ll
introduce two broad categories of open source software licenses
(copyleft and permissive) and describe examples of each.</p>
<p><strong>Learning Outcomes:</strong></p>
<ul>
<li><p>Understand what a license is and why software licenses are
necessary for sharing and reusing software</p></li>
<li><p>Be able to describe the difference between permissive and
copyleft software licenses</p></li>
<li><p>Understand factors that may constrain the license researchers can
apply to the code they create. These include the researcher’s
professional context (e.g., university policies) and the licensing
status of any code be reused or adapted.</p></li>
<li><p>Repository license requirements.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><h3
id="module-6-project-structure-not-covered-in-pilot-workshop">Module 6:
Project Structure (not covered in pilot workshop)</h3></td>
</tr>
<tr class="even">
<td><p><strong>Mode(s):</strong> <em>Lecture</em></p>
<p><strong>Estimated Time:</strong> <em>20 mins</em></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overview</strong></p>
<p>We’ll end the workshop by describing some common practices for
organizing datasets with code components.</p>
<p><strong>Learning Outcomes</strong></p>
<ul>
<li><p>Understanding why project structures are important for
reproducible workflows</p></li>
<li><p>Familiarity with file and directory naming conventions for
research software projects</p></li>
<li><p>Implement project templates used in the research computing
community.</p></li>
<li><p>Identify factors that may affect how a project should be
organized</p></li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="hands-on-curation-exercise">Hands-on Curation
Exercise</h2></td>
</tr>
<tr class="even">
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Estimated Time</strong>: 40mins.</p>
<p><strong>Hands-on Dataset Activity:</strong></p>
<p>We have provided a list of datasets that include software components.
Working in a small group, choose a dataset from the list and review it
as a group. Identify 3-4 aspects of the datasets that can be improved
and draft an email to the dataset author with a list of changes and/or
questions to consider. Use the checklist (below) to guide your review of
the submission.</p></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="additional-resources">Additional Resources </h2></td>
</tr>
<tr class="even">
<td><ul>
<li><p><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/Code_CurationChecklist.pdf">Curating Code Checklist</a></p></li>
<li><p><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/code-deposit-example.zip">Code Deposit Example Files (discussed in presentation)</a></p></li>
<li><p><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/References.pdf">References</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h2 id="bibliography-resources">Bibliography &amp; Resources
</h2></td>
</tr>
<tr class="even">
<td><p>Foundations for Curating Research Software (must-cite
literature)</p>
<ul>
<li><p>Barker, M., Chue Hong, N. P., Katz, D. S., Lamprecht, A.-L.,
Martinez-Ortiz, C., Psomopoulos, F., Harrow, J., Castro, L. J.,
Gruenpeter, M., Martinez, P. A., &amp; Honeyman, T. (2022). Introducing
the FAIR Principles for research software. Scientific Data, 9(1),
Article 1. <a
href="https://doi.org/10.1038/s41597-022-01710-x"><u>https://doi.org/10.1038/s41597-022-01710-x</u></a></p></li>
<li><p>Research Software Engineering with Python (The Alan Turing
Institute): <a
href="https://alan-turing-institute.github.io/rse-course/html/index.html#support-and-contributing"><u>Research
Software Engineering with Python — Research Software Engineering with
Python (alan-turing-institute.github.io)</u></a></p></li>
</ul>
<p>Conceptualizing Research Software</p>
<ul>
<li><p>Defining Research Software: a controversial discussion (<a
href="https://doi.org/10.5281/zenodo.5504016"><u>https://doi.org/10.5281/zenodo.5504016</u></a>)</p></li>
<li><p>Defining Roles of Research Software (<a
href="https://upstream.force11.org/defining-the-roles-of-research-software/"><u>https://upstream.force11.org/defining-the-roles-of-research-software/</u></a>)</p></li>
</ul>
<p>Software Licensing</p>
<ul>
<li><p>Morin, A., Urban, J., &amp; Sliz, P. (2012). A Quick Guide to
Software Licensing for the Scientist-Programmer. PLOS Computational
Biology, 8(7), e1002598. <a
href="https://doi.org/10.1371/journal.pcbi.1002598"><u>https://doi.org/10.1371/journal.pcbi.1002598</u></a></p></li>
<li><p>Stodden, V. (2009). The Legal Framework for Reproducible
Scientific Research: Licensing and Copyright. Computing in Science
Engineering, 11(1), 35–40. <a
href="https://doi.org/10.1109/MCSE.2009.19"><u>https://doi.org/10.1109/MCSE.2009.19</u></a></p></li>
<li><p>OSI’s open source definition (<a
href="https://opensource.org/definition-annotated/"><u>https://opensource.org/definition-annotated/</u></a>)</p></li>
<li><p>TLDR Legan (useful guide for comparing the characteristics of
different licenses <a
href="https://tldrlegal.com/"><u>https://tldrlegal.com/</u></a>)</p></li>
<li><p>Copyright Guide for Scientific Software: <a
href="https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf"><u>https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf</u></a></p></li>
</ul>
<p>Documentation best practices</p>
<p>READMEs</p>
<ul>
<li><p>A guide for READMEs: <a
href="https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices"><u>https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices</u></a></p></li>
<li><p>A browser-based template for READMEs:
https://www.makeareadme.com/</p></li>
<li><p>R-specific README guide <a
href="https://github.com/benmarwick/rrtools"><u>https://github.com/benmarwick/rrtools</u></a></p></li>
<li><p>Python-specific README guide <a
href="https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html"><u>https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html</u></a></p></li>
<li><p>Cornell README template (for data): <a
href="https://data.research.cornell.edu/content/readme"><u>https://data.research.cornell.edu/content/readme</u></a></p></li>
</ul>
<p>Research Software Engineering Practices (in general):</p>
<ul>
<li><p>“Software Engineering Practices in Academia: Promoting the
3Rs—Readability, Resilience, and Reuse”: <a
href="https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2"><u>https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2</u></a></p></li>
</ul>
<p>Dependency Management (overview of the challenge)</p>
<ul>
<li><p>Blog post by Noah Brenowitz <a
href="https://www.noahbrenowitz.com/post/2021-version-pinning/"><u>https://www.noahbrenowitz.com/post/2021-version-pinning/</u></a></p></li>
<li><p>Beaulieu-Jones, B., Greene, C. Reproducibility of computational
workflows is automated using continuous analysis. <em>Nat
Biotechnol</em> <strong>35</strong>, 342–346 (2017). <a
href="https://doi.org/10.1038/nbt.3780"><u>https://doi.org/10.1038/nbt.3780</u></a></p></li>
<li><p>Blog post by Alex Remedios (Python-specific, some interesting
thoughts on pinning dependencies) <a
href="https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa"><u>https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa</u></a></p></li>
</ul>
<p>Empirical studies of research software</p>
<ul>
<li><p>The Rise of GitHub in Scholarly Publications:<br />
<a
href="https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15"><u>https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15</u></a></p></li>
<li><p>A large-scale study on research code quality and execution <a
href="https://www.nature.com/articles/s41597-022-01143-6"><u>https://www.nature.com/articles/s41597-022-01143-6</u></a></p></li>
</ul>
<p>Tools and Standards for Research Software &amp; Reproducibility</p>
<ul>
<li><p>CodeMeta - metadata standard (<a
href="https://codemeta.github.io/user-guide/"><u>https://codemeta.github.io/user-guide/</u></a>)</p></li>
<li><p>Software Heritage Archive - code repository (<a
href="https://archive.softwareheritage.org"><u>https://archive.softwareheritage.org</u></a>)</p></li>
<li><p>ReproZip! - packaging reproducible bundles (<a
href="https://www.reprozip.org/"><u>https://www.reprozip.org/</u></a>)</p></li>
<li><p>Zenodo - general purpose repository with github integration (<a
href="https://zenodo.org"><u>https://zenodo.org</u></a>)</p></li>
<li><p>Git / GitHub / GitLab</p></li>
<li><p>BinderHub - platform for sharing reproducible code (<a
href="https://binderhub.readthedocs.io"><u>https://binderhub.readthedocs.io</u></a>)</p></li>
<li><p>Singularity</p></li>
<li><p>WholeTale (<a
href="https://wholetale.org/"><u>https://wholetale.org/</u></a>)</p></li>
<li><p>Poetry (<a href="https://python-poetry.org/"><u>Poetry - Python
dependency management and packaging made easy
(python-poetry.org)</u></a></p></li>
<li><p>Renv for R</p></li>
<li><p>Sinfo for Python (<a
href="https://pypi.org/project/sinfo/"><u>https://pypi.org/project/sinfo/</u></a>)</p></li>
</ul>
<p>Relevant Communities, Organizations, and Projects</p>
<ul>
<li><p>Software Sustainability Institute (<a
href="https://www.software.ac.uk/"><u>https://www.software.ac.uk/</u></a>)</p></li>
<li><p>Software Preservation Network (<a
href="https://www.softwarepreservationnetwork.org/"><u>https://www.softwarepreservationnetwork.org/</u></a>)</p></li>
<li><p>Software Heritage (<a
href="https://www.softwareheritage.org/"><u>https://www.softwareheritage.org/</u></a>)</p></li>
<li><p>US Research Software Engineering Association (<a
href="https://us-rse.org/"><u>https://us-rse.org/</u></a>)</p></li>
<li><p>Carpentries (<a
href="https://carpentries.org/"><u>https://carpentries.org/</u></a>)</p></li>
<li><p>Force11 (<a
href="https://force11.org/"><u>https://force11.org/</u></a>)</p></li>
<li><p>Journal of Open Source Software (<a
href="https://joss.theoj.org/"><u>https://joss.theoj.org/</u></a>)</p></li>
<li><p>The Turing Way (<a
href="https://the-turing-way.netlify.app/welcome"><u>https://the-turing-way.netlify.app/welcome</u></a>)</p></li>
<li><p>PyOpenSci (<a
href="https://www.pyopensci.org"><u>https://www.pyopensci.org</u></a>)</p></li>
<li><p>Cornell’s “Results Reproduction” project : <a
href="https://socialsciences.cornell.edu/research-support/R-squared"><u>https://socialsciences.cornell.edu/research-support/R-squared</u></a></p></li>
<li><p>Johns Hopkins Data Science “Reproducibility In Cancer
Informatics” <a
href="https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html"><u>https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html</u></a>.</p></li>
</ul>
<p>Programming languages commonly used in research (and observed in
curation workflows)</p>
<ul>
<li><p>General Overview (MATLAB, Python, R)</p>
<ul>
<li><p><a
href="https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e"><u>https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e</u></a></p></li>
</ul></li>
<li><p>Codecademy- Python (<a
href="https://www.codecademy.com/resources/blog/what-is-python-used-for/"><u>https://www.codecademy.com/resources/blog/what-is-python-used-for/</u></a>)</p></li>
<li><p>Codecademy- R (<a
href="https://www.codecademy.com/resources/blog/what-is-r-used-for/"><u>https://www.codecademy.com/resources/blog/what-is-r-used-for/</u></a>)</p></li>
<li><p>Coursera - Python (<a
href="https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python"><u>https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python</u></a>)</p></li>
<li><p>MATLAB Introductions:</p>
<ul>
<li><p><a
href="https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm"><u>https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm</u></a></p></li>
<li><p><a
href="https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners"><u>https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners</u></a></p></li>
</ul></li>
<li><p>MATLAB in chemical and petrochemical research: <a
href="https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html"><u>https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html</u></a></p></li>
<li><p>Association for Psychological Science: <a
href="https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r"><u>https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r</u></a></p></li>
<li><p>American Psychological Association: <a
href="https://psycnet.apa.org/record/2014-21523-009"><u>https://psycnet.apa.org/record/2014-21523-009</u></a></p></li>
</ul></td>
</tr>
</tbody>
</table>