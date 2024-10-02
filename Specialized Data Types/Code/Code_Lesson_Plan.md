# Data Curation Network Lesson Plan: Curating Code


| Lesson Components | Lesson Description |
| ------------- | ------------- |
| Data Type | Software source code (e.g., Python, R, Matlab) |
| Primary fields or areas of use | All |
| Summary | This is a hands-on workshop introducing core conceptions of software curation, including operating systems, programming languages, dependencies, and documentation. Licensing, and project organization are planned additions. |
| Estimated time | 4 hours |
| Related primers | <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md">Jupyter
Notebooks</a> <a href="https://hdl.handle.net/2027.42/154686">Matlab</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Python%20Primer/python.md">Python</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md">R</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SAS%20Data%20Curation%20Primer/SAS-data-curation-primer.md">SAS</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SPSS%20Data%20Curation%20Primer/SPSS-data-curation-primer.md">SPSS</a> |
| Lesson Components | Lesson Description |
| Lesson Components | Lesson Description |
| Lesson Components | Lesson Description |
| Lesson Components | Lesson Description |
| Lesson Components | Lesson Description |




<a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md">Jupyter
Notebooks</a> <a href="https://hdl.handle.net/2027.42/154686">Matlab</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Python%20Primer/python.md">Python</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md">R</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SAS%20Data%20Curation%20Primer/SAS-data-curation-primer.md">SAS</a> <a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SPSS%20Data%20Curation%20Primer/SPSS-data-curation-primer.md">SPSS</a>



<td><strong>Link to Slides</strong></td>
<td><a href="https://docs.google.com/presentation/d/1xMkrJkQEYCNNAsMGYCiNqRcN2WXH3P0xXb98O2KtSMk/edit#slide=id.g28fceffc8a9_0_308">Code Lecture Slides</a>


<td><strong>Date created</strong></td>
<td>October 2023</td>
</tr>
<tr class="odd">
<td><strong>Created by</strong></td>
<td>Talya Cooper, New York University, <a
href="https://orcid.org/0000-0003-4241-6330">https://orcid.org/0000-0003-4241-6330</a>
Greg Janée, University of California at Santa Barbara, <a
href="https://orcid.org/0000-0001-8785-0021">https://orcid.org/0000-0001-8785-0021</a>
Kay P Maye, Tulane University, <a
href="https://orcid.org/0000-0001-8615-1616">https://orcid.org/0000-0001-8615-1616</a>
Nick Ruhs, Florida State University, <a
href="https://orcid.org/0000-0002-3311-2661">https://orcid.org/0000-0002-3311-2661</a>
Seth Erickson, University of California at Santa Barbara, <a
href="https://orcid.org/0000-0002-5570-7201">https://orcid.org/0000-0002-5570-7201</a></td>
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
<td><strong>Learning Outcomes:</strong>
By the end of this workshop, learners should be able to …
<ul>
<li>Identify and explain real-world examples of how differences
between computing environments lead to reproducibility
problems.</li>
<li>Navigate significant differences between major operating systems
and understand how they affect the reusability of software</li>
<li>Identify several common programming languages used in research
computing and the file types and tools associated with each.</li>
<li>Identify and document dependencies used in research software for
common programming languages.</li>
<li>Identify and improve different types of documentation associated
with source code and research software.</li>
<li>Describe differences between software licenses and non-software
licenses, and differences between different kinds of open source
software licenses.</li>
<li>Implement commonly used project organization strategies used in
the research community.</li>
</ul>
<strong>Key Terms:</strong>
<ul>
<li><strong>Source Code</strong> - plain text, written in a
programming language, that can be run on a computer using an interpreter
or compiled into runnable machine code by a compiler.</li>
<li><strong>Operating System</strong>: system software that manages
computer hardware and software resources, and provides common services
for computer programs.</li>
<li><strong>File</strong>: a unit of stored data or information that
is managed by an operating system and uniquely identified by a “path”
(the file’s location within a hierarchical file system).</li>
<li><strong>Programming Language:</strong> a language used to develop
software programs, scripts, or other sets of instructions for a computer
to execute</li>
<li><strong>Software Dependency:</strong> Anything that a piece of
software relies on to function correctly, that is external to the
software itself.</li>
<li><strong>Documentation / README</strong>: Documentation written by
software authors or curators, primarily for the purpose of facilitating
the software’s reuse.</li>
<li><strong>Integrated Development Environment</strong> (IDE):
Software that facilitates writing and debugging software source
code.</li>
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
<td><strong>Required Tools/Software:</strong>
We recommend using a source code editor (Visual Studio Code or
Sublime) to view example files, but this is not required.
<strong>Dataset Citations:</strong>
Bump, Joseph K; Beyer, Dean; O'Neil, Shawn. (2019). Code, data, and
metadata document for the manuscript: Territorial landscapes:
incorporating density-dependence into wolf resource selection study
designs. Retrieved from the Data Repository for the University of
Minnesota, <a
href="https://doi.org/10.13020/s40h-fv72">https://doi.org/10.13020/s40h-fv72</a>.
Heuschele, Deborah; Furuta, Daniel; Smith, Kevin; Marchetto, Peter.
(2022). Data and analysis code for "Capturing High Resolution Plant
Movement in the Field". Retrieved from the Data Repository for the
University of Minnesota, <a
href="https://doi.org/10.13020/7e6x-8f36">https://doi.org/10.13020/7e6x-8f36</a>.</td>
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
<td><strong>Mode(s):</strong> Presentation, Case Study
<strong>Estimated time: </strong>10 mins</td>
</tr>
<tr class="odd">
<td><strong>Overview</strong>:
We start the workshops with a short case study (“Willoughby-Hoye
Scripts”) illustrating the challenge of reproducibility and the
importance of software curation. Core concepts that structure the rest
of the workshop are also introduced: computing platforms, programming
languages, dependencies, documentation, licensing, and project
organization.
<strong>Learning Outcomes</strong>:
<ul>
<li>Identify and explain a real-world example of how differences
between computing environments can lead to non-reproducible
code.</li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-1-computing-platforms">Module 1: Computing
Platforms</h3></td>
</tr>
<tr class="odd">
<td><strong>Mode(s):</strong> Lecture, Demonstration
<strong>Estimated time:</strong> 30 mins</td>
</tr>
<tr class="even">
<td><strong>Overview:</strong>
This module will introduce some of the basic characteristics of
computing platforms, and how incompatibilities across platforms can
cause programs to not run at all, to operate incorrectly, or to produce
different output.
<strong>Learning Outcomes:</strong>
<ul>
<li>Understand elements of computing platforms</li>
<li>Understand differences between compiled and interpreted
languages</li>
<li>Understand obstacles to reproducibility</li>
<li>Understand implications for curation</li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="module-2-programming-languages">Module 2: Programming
Languages</h3></td>
</tr>
<tr class="even">
<td><strong>Mode(s):</strong> Lecture
<strong>Estimated time: </strong> 30 mins</td>
</tr>
<tr class="odd">
<td><strong>Overview:</strong>
This module will introduce the concept of a programming language and
will then discuss three common programming languages that are used by
researchers–Python, R, and MATLAB. Learners will become familiar with
the applicability of these three programming languages, as well as file
formats that are used by each language for program files or scripts.
They will also be introduced to integrated development environments and
how they are utilized with programming languages and software.
<strong>Learning Outcomes:</strong>
<ul>
<li>Describe common programming languages used in academic research
and their applications</li>
<li>Identify key file types and extensions associated with MATLAB,
Python, and R</li>
<li>Introduce common Integrated Development Environments (IDE) and
Notebooks for these programming language</li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-3-dependencies">Module 3: Dependencies</h3></td>
</tr>
<tr class="odd">
<td><strong>Mode(s):</strong> Lecture, Activity
<strong>Estimated time: </strong>30 mins</td>
</tr>
<tr class="even">
<td><strong>Overview:</strong>
This module will discuss software dependencies: how researchers use
them and keep them up to date; how to observe their use in code in R,
Python, and MATLAB; and the potential problems they can pose for
reproducibility and curation. Learners will become familiar with the
idea of versioning and the concept of package managers. They will also
learn how to recommend that code creators document dependencies for
maximal reproducibility.
<strong>Learning Outcomes:</strong>
<ul>
<li>Define “dependency” and learn why dependencies are used</li>
<li>Identify when dependencies are being used in code</li>
<li>Gain familiarity with package managers and versioning</li>
<li>Learn several ways to record dependencies–via README,
programmatically, and through the use of containerization</li>
</ul></td>
</tr>
<tr class="odd">
<td><h3 id="module-4-documentation"> Module 4: Documentation</h3></td>
</tr>
<tr class="even">
<td><strong>Mode(s):</strong> Lecture, Small Group Discussion,
Individual Activity
<strong>Estimated time:</strong> 30 mins - 40
mins</td>
</tr>
<tr class="odd">
<td><strong>Overview:</strong>
This module introduces learners to methods for documenting research
software. Documentation helps researchers, curators, and users find,
access, and implement research software. Learners will be able to
identify how to use documentation to inform their curation practices and
how to offer edits to depositors.
<strong>Learning Outcomes:</strong>
<ul>
<li>Identify types of research software documentation and how they
can be useful during the curation process</li>
<li>Make suggestions for research software documentation (README,
Commenting, Markdown, etc.)</li>
<li>Review and offer edits to README files/outlines for research
software</li>
</ul></td>
</tr>
<tr class="even">
<td><h3 id="module-5-licensing-not-covered-in-pilot-workshop">Module 5:
Licensing (not covered in pilot workshop)</h3></td>
</tr>
<tr class="odd">
<td><strong>Mode(s):</strong> Lecture
<strong>Estimated time: </strong>30 mins</td>
</tr>
<tr class="even">
<td><strong>Overview:</strong>
A license is legal permission for others to copy, modify, and share
your work. An open source software license is one that permits free
distribution of source code and the creation of derived works. We’ll
introduce two broad categories of open source software licenses
(copyleft and permissive) and describe examples of each.
<strong>Learning Outcomes:</strong>
<ul>
<li>Understand what a license is and why software licenses are
necessary for sharing and reusing software</li>
<li>Be able to describe the difference between permissive and
copyleft software licenses</li>
<li>Understand factors that may constrain the license researchers can
apply to the code they create. These include the researcher’s
professional context (e.g., university policies) and the licensing
status of any code be reused or adapted.</li>
<li>Repository license requirements.</li>
</ul></td>
</tr>
<tr class="odd">
<td><h3
id="module-6-project-structure-not-covered-in-pilot-workshop">Module 6:
Project Structure (not covered in pilot workshop)</h3></td>
</tr>
<tr class="even">
<td><strong>Mode(s):</strong> Lecture
<strong>Estimated Time:</strong> 20 mins</td>
</tr>
<tr class="odd">
<td><strong>Overview</strong>
We’ll end the workshop by describing some common practices for
organizing datasets with code components.
<strong>Learning Outcomes</strong>
<ul>
<li>Understanding why project structures are important for
reproducible workflows</li>
<li>Familiarity with file and directory naming conventions for
research software projects</li>
<li>Implement project templates used in the research computing
community.</li>
<li>Identify factors that may affect how a project should be
organized</li>
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
<td><strong>Estimated Time</strong>: 40mins.
<strong>Hands-on Dataset Activity:</strong>
We have provided a list of datasets that include software components.
Working in a small group, choose a dataset from the list and review it
as a group. Identify 3-4 aspects of the datasets that can be improved
and draft an email to the dataset author with a list of changes and/or
questions to consider. Use the checklist (below) to guide your review of
the submission.</td>
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
<li><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/Code_CurationChecklist.pdf">Curating Code Checklist</a></li>
<li><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/code-deposit-example.zip">Code Deposit Example Files (discussed in presentation)</a></li>
<li><a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/References.pdf">References</a></li>
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
<td>Foundations for Curating Research Software (must-cite
literature)
<ul>
<li>Barker, M., Chue Hong, N. P., Katz, D. S., Lamprecht, A.-L.,
Martinez-Ortiz, C., Psomopoulos, F., Harrow, J., Castro, L. J.,
Gruenpeter, M., Martinez, P. A., &amp; Honeyman, T. (2022). Introducing
the FAIR Principles for research software. Scientific Data, 9(1),
Article 1. <a
href="https://doi.org/10.1038/s41597-022-01710-x">https://doi.org/10.1038/s41597-022-01710-x</a></li>
<li>Research Software Engineering with Python (The Alan Turing
Institute): <a
href="https://alan-turing-institute.github.io/rse-course/html/index.html#support-and-contributing">Research
Software Engineering with Python — Research Software Engineering with
Python (alan-turing-institute.github.io)</a></li>
</ul>
Conceptualizing Research Software
<ul>
<li>Defining Research Software: a controversial discussion (<a
href="https://doi.org/10.5281/zenodo.5504016">https://doi.org/10.5281/zenodo.5504016</a>)</li>
<li>Defining Roles of Research Software (<a
href="https://upstream.force11.org/defining-the-roles-of-research-software/">https://upstream.force11.org/defining-the-roles-of-research-software/</a>)</li>
</ul>
Software Licensing
<ul>
<li>Morin, A., Urban, J., &amp; Sliz, P. (2012). A Quick Guide to
Software Licensing for the Scientist-Programmer. PLOS Computational
Biology, 8(7), e1002598. <a
href="https://doi.org/10.1371/journal.pcbi.1002598">https://doi.org/10.1371/journal.pcbi.1002598</a></li>
<li>Stodden, V. (2009). The Legal Framework for Reproducible
Scientific Research: Licensing and Copyright. Computing in Science
Engineering, 11(1), 35–40. <a
href="https://doi.org/10.1109/MCSE.2009.19">https://doi.org/10.1109/MCSE.2009.19</a></li>
<li>OSI’s open source definition (<a
href="https://opensource.org/definition-annotated/">https://opensource.org/definition-annotated/</a>)</li>
<li>TLDR Legan (useful guide for comparing the characteristics of
different licenses <a
href="https://tldrlegal.com/">https://tldrlegal.com/</a>)</li>
<li>Copyright Guide for Scientific Software: <a
href="https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf">https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf</a></li>
</ul>
Documentation best practices
READMEs
<ul>
<li>A guide for READMEs: <a
href="https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices">https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices</a></li>
<li>A browser-based template for READMEs:
https://www.makeareadme.com/</li>
<li>R-specific README guide <a
href="https://github.com/benmarwick/rrtools">https://github.com/benmarwick/rrtools</a></li>
<li>Python-specific README guide <a
href="https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html">https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html</a></li>
<li>Cornell README template (for data): <a
href="https://data.research.cornell.edu/content/readme">https://data.research.cornell.edu/content/readme</a></li>
</ul>
Research Software Engineering Practices (in general):
<ul>
<li>“Software Engineering Practices in Academia: Promoting the
3Rs—Readability, Resilience, and Reuse”: <a
href="https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2">https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2</a></li>
</ul>
Dependency Management (overview of the challenge)
<ul>
<li>Blog post by Noah Brenowitz <a
href="https://www.noahbrenowitz.com/post/2021-version-pinning/">https://www.noahbrenowitz.com/post/2021-version-pinning/</a></li>
<li>Beaulieu-Jones, B., Greene, C. Reproducibility of computational
workflows is automated using continuous analysis. Nat
Biotechnol <strong>35</strong>, 342–346 (2017). <a
href="https://doi.org/10.1038/nbt.3780">https://doi.org/10.1038/nbt.3780</a></li>
<li>Blog post by Alex Remedios (Python-specific, some interesting
thoughts on pinning dependencies) <a
href="https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa">https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa</a></li>
</ul>
Empirical studies of research software
<ul>
<li>The Rise of GitHub in Scholarly Publications:<br />
<a
href="https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15">https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15</a></li>
<li>A large-scale study on research code quality and execution <a
href="https://www.nature.com/articles/s41597-022-01143-6">https://www.nature.com/articles/s41597-022-01143-6</a></li>
</ul>
Tools and Standards for Research Software &amp; Reproducibility
<ul>
<li>CodeMeta - metadata standard (<a
href="https://codemeta.github.io/user-guide/">https://codemeta.github.io/user-guide/</a>)</li>
<li>Software Heritage Archive - code repository (<a
href="https://archive.softwareheritage.org">https://archive.softwareheritage.org</a>)</li>
<li>ReproZip! - packaging reproducible bundles (<a
href="https://www.reprozip.org/">https://www.reprozip.org/</a>)</li>
<li>Zenodo - general purpose repository with github integration (<a
href="https://zenodo.org">https://zenodo.org</a>)</li>
<li>Git / GitHub / GitLab</li>
<li>BinderHub - platform for sharing reproducible code (<a
href="https://binderhub.readthedocs.io">https://binderhub.readthedocs.io</a>)</li>
<li>Singularity</li>
<li>WholeTale (<a
href="https://wholetale.org/">https://wholetale.org/</a>)</li>
<li>Poetry (<a href="https://python-poetry.org/">Poetry - Python
dependency management and packaging made easy
(python-poetry.org)</a></li>
<li>Renv for R</li>
<li>Sinfo for Python (<a
href="https://pypi.org/project/sinfo/">https://pypi.org/project/sinfo/</a>)</li>
</ul>
Relevant Communities, Organizations, and Projects
<ul>
<li>Software Sustainability Institute (<a
href="https://www.software.ac.uk/">https://www.software.ac.uk/</a>)</li>
<li>Software Preservation Network (<a
href="https://www.softwarepreservationnetwork.org/">https://www.softwarepreservationnetwork.org/</a>)</li>
<li>Software Heritage (<a
href="https://www.softwareheritage.org/">https://www.softwareheritage.org/</a>)</li>
<li>US Research Software Engineering Association (<a
href="https://us-rse.org/">https://us-rse.org/</a>)</li>
<li>Carpentries (<a
href="https://carpentries.org/">https://carpentries.org/</a>)</li>
<li>Force11 (<a
href="https://force11.org/">https://force11.org/</a>)</li>
<li>Journal of Open Source Software (<a
href="https://joss.theoj.org/">https://joss.theoj.org/</a>)</li>
<li>The Turing Way (<a
href="https://the-turing-way.netlify.app/welcome">https://the-turing-way.netlify.app/welcome</a>)</li>
<li>PyOpenSci (<a
href="https://www.pyopensci.org">https://www.pyopensci.org</a>)</li>
<li>Cornell’s “Results Reproduction” project : <a
href="https://socialsciences.cornell.edu/research-support/R-squared">https://socialsciences.cornell.edu/research-support/R-squared</a></li>
<li>Johns Hopkins Data Science “Reproducibility In Cancer
Informatics” <a
href="https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html">https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html</a>.</li>
</ul>
Programming languages commonly used in research (and observed in
curation workflows)
<ul>
<li>General Overview (MATLAB, Python, R)
<ul>
<li><a
href="https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e">https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e</a></li>
</ul></li>
<li>Codecademy- Python (<a
href="https://www.codecademy.com/resources/blog/what-is-python-used-for/">https://www.codecademy.com/resources/blog/what-is-python-used-for/</a>)</li>
<li>Codecademy- R (<a
href="https://www.codecademy.com/resources/blog/what-is-r-used-for/">https://www.codecademy.com/resources/blog/what-is-r-used-for/</a>)</li>
<li>Coursera - Python (<a
href="https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python">https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python</a>)</li>
<li>MATLAB Introductions:
<ul>
<li><a
href="https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm">https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm</a></li>
<li><a
href="https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners">https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners</a></li>
</ul></li>
<li>MATLAB in chemical and petrochemical research: <a
href="https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html">https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html</a></li>
<li>Association for Psychological Science: <a
href="https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r">https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r</a></li>
<li>American Psychological Association: <a
href="https://psycnet.apa.org/record/2014-21523-009">https://psycnet.apa.org/record/2014-21523-009</a></li>
</ul></td>
</tr>
</tbody>
</table>