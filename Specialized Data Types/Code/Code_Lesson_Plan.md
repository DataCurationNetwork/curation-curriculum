# Data Curation Network Lesson Plan: Curating Code


| Lesson Components | Lesson Description |
| ------------- | ------------- |
| Data Type | Software source code (e.g., Python, R, Matlab) |
| Primary fields or areas of use | All |
| Summary | This is a hands-on workshop introducing core conceptions of software curation, including operating systems, programming languages, dependencies, and documentation. Licensing, and project organization are planned additions. |
| Estimated time | 4 hours |
| Related primers | <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Jupyter%20Notebook%20Data%20Curation%20Primer/Jupyter%20Notebooks%20Data%20Curation%20Primer.md">Jupyter Notebooks</a></li> <li><a href="https://hdl.handle.net/2027.42/154686">Matlab</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/Python%20Primer/python.md">Python</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/R%20Data%20Curation%20Primer/R-data-curation-primer.md">R</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SAS%20Data%20Curation%20Primer/SAS-data-curation-primer.md">SAS</a></li> <li><a href="https://github.com/DataCurationNetwork/data-primers/blob/master/SPSS%20Data%20Curation%20Primer/SPSS-data-curation-primer.md">SPSS</a></li> |
| Link to slides | <a href="https://docs.google.com/presentation/d/1xMkrJkQEYCNNAsMGYCiNqRcN2WXH3P0xXb98O2KtSMk/edit#slide=id.g28fceffc8a9_0_308">Code Lecture Slides</a> |
| Date Created | October 2023 |
| Created By | Talya Cooper, New York University, <a href="https://orcid.org/0000-0003-4241-6330">https://orcid.org/0000-0003-4241-6330</a> <br><br> Greg Janée, University of California at Santa Barbara, <a href="https://orcid.org/0000-0001-8785-0021">https://orcid.org/0000-0001-8785-0021</a> <br><br> Kay P Maye, Tulane University, <a href="https://orcid.org/0000-0001-8615-1616">https://orcid.org/0000-0001-8615-1616</a> <br><br> Nick Ruhs, Florida State University, <a href="https://orcid.org/0000-0002-3311-2661">https://orcid.org/0000-0002-3311-2661</a> <br><br> Seth Erickson, University of California at Santa Barbara, <a href="https://orcid.org/0000-0002-5570-7201">https://orcid.org/0000-0002-5570-7201</a> |


# Objectives and Vocabulary
## Learning Outcomes:
By the end of this workshop, learners should be able to …
- Identify and explain real-world examples of how differences
between computing environments lead to reproducibility
problems.
- Navigate significant differences between major operating systems
and understand how they affect the reusability of software
- Identify several common programming languages used in research
computing and the file types and tools associated with each.
- Identify and document dependencies used in research software for
common programming languages.
- Identify and improve different types of documentation associated
with source code and research software.
- Describe differences between software licenses and non-software
licenses, and differences between different kinds of open source
software licenses.
- Implement commonly used project organization strategies used in
the research community.

## Key Terms: 

- Source Code - plain text, written in a
programming language, that can be run on a computer using an interpreter
or compiled into runnable machine code by a compiler.
- Operating System: system software that manages
computer hardware and software resources, and provides common services
for computer programs.
- File: a unit of stored data or information that
is managed by an operating system and uniquely identified by a “path”
(the file’s location within a hierarchical file system).
- Programming Language: a language used to develop
software programs, scripts, or other sets of instructions for a computer
to execute.
- Software Dependency: Anything that a piece of
software relies on to function correctly, that is external to the
software itself.
- Documentation / README: Documentation written by
software authors or curators, primarily for the purpose of facilitating
the software’s reuse.
- Integrated Development Environment (IDE):
Software that facilitates writing and debugging software source
code.

# Dataset(s) for Lesson

Required Tools/Software:

We recommend using a source code editor (Visual Studio Code or
Sublime) to view example files, but this is not required.

## Dataset Citations:

Bump, Joseph K; Beyer, Dean; O'Neil, Shawn. (2019). Code, data, and
metadata document for the manuscript: Territorial landscapes:
incorporating density-dependence into wolf resource selection study
designs. Retrieved from the Data Repository for the University of
Minnesota, <a href="https://doi.org/10.13020/s40h-fv72">https://doi.org/10.13020/s40h-fv72</a>.

Heuschele, Deborah; Furuta, Daniel; Smith, Kevin; Marchetto, Peter.
(2022). Data and analysis code for "Capturing High Resolution Plant
Movement in the Field". Retrieved from the Data Repository for the
University of Minnesota, <a
href="https://doi.org/10.13020/7e6x-8f36">https://doi.org/10.13020/7e6x-8f36</a>.

# Outline and Content
## Introduction

Mode(s): Presentation, Case Study <br>
Estimated time: 10 mins

Overview:
We start the workshops with a short case study (“Willoughby-Hoye
Scripts”) illustrating the challenge of reproducibility and the
importance of software curation. Core concepts that structure the rest
of the workshop are also introduced: computing platforms, programming
languages, dependencies, documentation, licensing, and project
organization.

Learning Outcomes:

- Identify and explain a real-world example of how differences
between computing environments can lead to non-reproducible
code.

## Module 1: Computing Platforms

Mode(s): Lecture, Demonstration <br>
Estimated time: 30 mins

Overview:
This module will introduce some of the basic characteristics of
computing platforms, and how incompatibilities across platforms can
cause programs to not run at all, to operate incorrectly, or to produce
different output.

Learning Outcomes:
- Understand elements of computing platforms
- Understand differences between compiled and interpreted
languages
- Understand obstacles to reproducibility
- Understand implications for curation

## Module 2: Programming Languages

Mode(s): Lecture <br>
Estimated time:  30 mins

Overview:
This module will introduce the concept of a programming language and
will then discuss three common programming languages that are used by
researchers–Python, R, and MATLAB. Learners will become familiar with
the applicability of these three programming languages, as well as file
formats that are used by each language for program files or scripts.
They will also be introduced to integrated development environments and
how they are utilized with programming languages and software.

Learning Outcomes:
- Describe common programming languages used in academic research
and their applications
- Identify key file types and extensions associated with MATLAB,
Python, and R
- Introduce common Integrated Development Environments (IDE) and
Notebooks for these programming language

## Module 3: Dependencies

Mode(s): Lecture, Activity <br>
Estimated time: 30 mins


Overview:
This module will discuss software dependencies: how researchers use
them and keep them up to date; how to observe their use in code in R,
Python, and MATLAB; and the potential problems they can pose for
reproducibility and curation. Learners will become familiar with the
idea of versioning and the concept of package managers. They will also
learn how to recommend that code creators document dependencies for
maximal reproducibility.

Learning Outcomes:
- Define “dependency” and learn why dependencies are used
- Identify when dependencies are being used in code
- Gain familiarity with package managers and versioning
- Learn several ways to record dependencies–via README,
programmatically, and through the use of containerization 


## Module 4: Documentation 

Mode(s): Lecture, Small Group Discussion,
Individual Activity <br>
Estimated time: 30 mins - 40
mins

Overview:
This module introduces learners to methods for documenting research
software. Documentation helps researchers, curators, and users find,
access, and implement research software. Learners will be able to
identify how to use documentation to inform their curation practices and
how to offer edits to depositors.

Learning Outcomes:
- Identify types of research software documentation and how they
can be useful during the curation process
- Make suggestions for research software documentation (README,
Commenting, Markdown, etc.)
- Review and offer edits to README files/outlines for research
software 


## Module 5: Licensing (not covered in pilot workshop)

Mode(s): Lecture <br>
Estimated time: 30 mins

Overview:
A license is legal permission for others to copy, modify, and share
your work. An open source software license is one that permits free
distribution of source code and the creation of derived works. We’ll
introduce two broad categories of open source software licenses
(copyleft and permissive) and describe examples of each.

Learning Outcomes:
- Understand what a license is and why software licenses are
necessary for sharing and reusing software
- Be able to describe the difference between permissive and
copyleft software licenses
- Understand factors that may constrain the license researchers can
apply to the code they create. These include the researcher’s
professional context (e.g., university policies) and the licensing
status of any code be reused or adapted.
- Repository license requirements.

## Module 6: Project Structure (not covered in pilot workshop)

Mode(s): Lecture <br>
Estimated Time: 20 mins

Overview
We’ll end the workshop by describing some common practices for
organizing datasets with code components.
Learning Outcomes

- Understanding why project structures are important for
reproducible workflows
- Familiarity with file and directory naming conventions for
research software projects
- Implement project templates used in the research computing
community.
- Identify factors that may affect how a project should be
organized

# Hands-on Curation Exercise

Estimated Time: 40mins.
Hands-on Dataset Activity:
We have provided a list of datasets that include software components.
Working in a small group, choose a dataset from the list and review it
as a group. Identify 3-4 aspects of the datasets that can be improved
and draft an email to the dataset author with a list of changes and/or
questions to consider. Use the checklist (below) to guide your review of
the submission.


# Additional Resources
- <a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/Code_CurationChecklist.pdf">Curating Code Checklist</a>
- <a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/Exercise%20Materials/code-deposit-example.zip">Code Deposit Example Files (discussed in presentation)</a>
- <a href="https://github.com/DataCurationNetwork/curation-curriculum/blob/b3ceb41b653b5bef5a1a3569bc005550b571b1a6/Specialized%20Data%20Types/Code/References.pdf">References</a></li>


# Bibliography & Resources

Foundations for Curating Research Software (must-cite
literature) <br>

- Barker, M., Chue Hong, N. P., Katz, D. S., Lamprecht, A.-L.,
Martinez-Ortiz, C., Psomopoulos, F., Harrow, J., Castro, L. J.,
Gruenpeter, M., Martinez, P. A., & Honeyman, T. (2022). Introducing
the FAIR Principles for research software. Scientific Data, 9(1),
Article 1. <a
href="https://doi.org/10.1038/s41597-022-01710-x">https://doi.org/10.1038/s41597-022-01710-x</a>
- Research Software Engineering with Python (The Alan Turing
Institute): <a
href="https://alan-turing-institute.github.io/rse-course/html/index.html#support-and-contributing">Research
Software Engineering with Python — Research Software Engineering with
Python (alan-turing-institute.github.io)</a>

Conceptualizing Research Software< br>

- Defining Research Software: a controversial discussion (<a
href="https://doi.org/10.5281/zenodo.5504016">https://doi.org/10.5281/zenodo.5504016</a>)
- Defining Roles of Research Software (<a
href="https://upstream.force11.org/defining-the-roles-of-research-software/">https://upstream.force11.org/defining-the-roles-of-research-software/</a>)</li>

Software Licensing

- Morin, A., Urban, J., & Sliz, P. (2012). A Quick Guide to
Software Licensing for the Scientist-Programmer. PLOS Computational
Biology, 8(7), e1002598. <a
href="https://doi.org/10.1371/journal.pcbi.1002598">https://doi.org/10.1371/journal.pcbi.1002598</a>
- Stodden, V. (2009). The Legal Framework for Reproducible
Scientific Research: Licensing and Copyright. Computing in Science
Engineering, 11(1), 35–40. <a
href="https://doi.org/10.1109/MCSE.2009.19">https://doi.org/10.1109/MCSE.2009.19</a>
- OSI’s open source definition (<a
href="https://opensource.org/definition-annotated/">https://opensource.org/definition-annotated/</a>)
- TLDR Legan (useful guide for comparing the characteristics of
different licenses <a
href="https://tldrlegal.com/">https://tldrlegal.com/</a>)
- Copyright Guide for Scientific Software: <a
href="https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf">https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/03/Copyright_Guide_for_Scientific_Software_12172019.pdf</a>

Documentation best practices<br>
READMEs

- A guide for READMEs: <a
href="https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices">https://www.welcometothejungle.com/en/articles/btc-readme-documentation-best-practices</a>
- A browser-based template for READMEs:
https://www.makeareadme.com/
- R-specific README guide <a
href="https://github.com/benmarwick/rrtools">https://github.com/benmarwick/rrtools</a>
- Python-specific README guide <a
href="https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html">https://www.pyopensci.org/python-package-guide/documentation/repository-files/readme-file-best-practices.html</a>
- Cornell README template (for data): <a
href="https://data.research.cornell.edu/content/readme">https://data.research.cornell.edu/content/readme</a>

Research Software Engineering Practices (in general): <br>

- “Software Engineering Practices in Academia: Promoting the
3Rs—Readability, Resilience, and Reuse”: <a
href="https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2">https://hdsr.mitpress.mit.edu/pub/f0f7h5cu/release/2</a> 

Dependency Management (overview of the challenge) <br>

- Blog post by Noah Brenowitz <a
href="https://www.noahbrenowitz.com/post/2021-version-pinning/">https://www.noahbrenowitz.com/post/2021-version-pinning/</a>
- Beaulieu-Jones, B., Greene, C. Reproducibility of computational
workflows is automated using continuous analysis. Nat
Biotechnol 35, 342–346 (2017). <a
href="https://doi.org/10.1038/nbt.3780">https://doi.org/10.1038/nbt.3780</a>
- Blog post by Alex Remedios (Python-specific, some interesting
thoughts on pinning dependencies) <a
href="https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa">https://towardsdatascience.com/devops-for-data-science-making-your-python-project-reproducible-f55646e110fa</a>

Empirical studies of research software <br>

- The Rise of GitHub in Scholarly Publications: <a
href="https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15">https://link.springer.com/chapter/10.1007/978-3-031-16802-4_15</a>
- A large-scale study on research code quality and execution <a
href="https://www.nature.com/articles/s41597-022-01143-6">https://www.nature.com/articles/s41597-022-01143-6</a>

Tools and Standards for Research Software & Reproducibility <br>

- CodeMeta - metadata standard (<a
href="https://codemeta.github.io/user-guide/">https://codemeta.github.io/user-guide/</a>)
- Software Heritage Archive - code repository (<a
href="https://archive.softwareheritage.org">https://archive.softwareheritage.org</a>)
- ReproZip! - packaging reproducible bundles (<a
href="https://www.reprozip.org/">https://www.reprozip.org/</a>)
- Zenodo - general purpose repository with github integration (<a
href="https://zenodo.org">https://zenodo.org</a>)
- Git / GitHub / GitLab<
- BinderHub - platform for sharing reproducible code (<a
href="https://binderhub.readthedocs.io">https://binderhub.readthedocs.io</a>)
- Singularity
- WholeTale (<a
href="https://wholetale.org/">https://wholetale.org/</a>)
- Poetry (<a href="https://python-poetry.org/">Poetry - Python
dependency management and packaging made easy
(python-poetry.org)</a>
- Renv for R 
- Sinfo for Python (<a
href="https://pypi.org/project/sinfo/">https://pypi.org/project/sinfo/</a>)

Relevant Communities, Organizations, and Projects <br>

- Software Sustainability Institute (<a
href="https://www.software.ac.uk/">https://www.software.ac.uk/</a>)
- Software Preservation Network (<a
href="https://www.softwarepreservationnetwork.org/">https://www.softwarepreservationnetwork.org/</a>)
- Software Heritage (<a
href="https://www.softwareheritage.org/">https://www.softwareheritage.org/</a>)
- US Research Software Engineering Association (<a
href="https://us-rse.org/">https://us-rse.org/</a>)
- Carpentries (<a
href="https://carpentries.org/">https://carpentries.org/</a>)
- Force11 (<a
href="https://force11.org/">https://force11.org/</a>)
- Journal of Open Source Software (<a
href="https://joss.theoj.org/">https://joss.theoj.org/</a>)
- The Turing Way (<a
href="https://the-turing-way.netlify.app/welcome">https://the-turing-way.netlify.app/welcome</a>)
- PyOpenSci (<a
href="https://www.pyopensci.org">https://www.pyopensci.org</a>)
- Cornell’s “Results Reproduction” project : <a
href="https://socialsciences.cornell.edu/research-support/R-squared">https://socialsciences.cornell.edu/research-support/R-squared</a>
- Johns Hopkins Data Science “Reproducibility In Cancer
Informatics” <a
href="https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html">https://jhudatascience.org/Reproducibility_in_Cancer_Informatics/index.html</a>.

Programming languages commonly used in research (and observed in
curation workflows) <br>

- General Overview (MATLAB, Python, R): <a
href="https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e">https://medium.com/@mygreatlearning/programming-languages-for-data-science-python-vs-r-vs-matlab-d3bfd04c991e</a>
- Codecademy- Python (<a
href="https://www.codecademy.com/resources/blog/what-is-python-used-for/">https://www.codecademy.com/resources/blog/what-is-python-used-for/</a>)
- Codecademy- R (<a
href="https://www.codecademy.com/resources/blog/what-is-r-used-for/">https://www.codecademy.com/resources/blog/what-is-r-used-for/</a>)
- Coursera - Python (<a
href="https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python">https://www.coursera.org/articles/what-is-python-used-for-a-beginners-guide-to-using-python</a>)
- MATLAB Introductions:
	- <a
href="https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm">https://cimss.ssec.wisc.edu/wxwise/class/aos340/spr00/whatismatlab.htm</a>
	- <a
href="https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners">https://www.simplilearn.com/tutorials/matlab-tutorial/what-is-matlab-introduction-for-beginners</a>
- MATLAB in chemical and petrochemical research: <a
href="https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html">https://www.mathworks.com/solutions/chemicals-and-petrochemicals.html</a>
- Association for Psychological Science: <a
href="https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r">https://www.psychologicalscience.org/observer/why-you-should-become-a-user-a-brief-introduction-to-r</a>
- American Psychological Association: <a
href="https://psycnet.apa.org/record/2014-21523-009">https://psycnet.apa.org/record/2014-21523-009</a>