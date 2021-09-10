## SSC 2022 Reproducibility workshop

**Blurb**: This workshop will equip participants with tools (Git/GitHub, R/Rstudio and `renv`- an R dependency management tool) and best practices for implementing data analysis workflows that promote collaboration and reproducibility. These tools and workflows are integral to creating reproducible and transparent research - research where the same result can be reached given the  same input, computational methods, and conditions, as well as one that has a history which records how and why decisions were made that shaped the analysis. These tools and principles have also transformed the teaching of statistics, facilitating the development of active and experiential learning.

### Some definitions to help us scope the workshop:

**Data science:** process of extracting insight from data through reproducible and auditable methods.

**Reproducibile analysis:** reaching the same result given the same input, computational methods, 
and conditions (from National Academy of Sciences, 2019).

**Auditable analysis:** an analysis with a readable record of the steps used to carryout
the analysis (*i.e.*, computer code) 
as well as a record of how the analysis methods evolved 
(*i.e.,* a version controlled project history) (from Parker, 2017 and Ram, 2013). 
This history is important for recording how and why decisions to use one method 
or another were made, among other things.  

Thoughts: writing code is important for creating reproducible and auditable analyses, but it is not enough. 
More is needed, including a recorded and shareable compute environment, and a version controlled history of the project.

### Possible workshop topics:

I assume the audience is most likely familiar with the R programming language (as opposed to Python) 
and would prefer to stay in an R-only world as opposed to moving into more devops like tools for 
compute environment managment.

- what is reproducibility and why is it important (60 min)
- the importance of reproducible coding habits (e.g., scripting, usethis, here) for portability and 're-run-ability' (60 minutes)
- version control (Git, mostly - concepts, mapping, understanding the basics of branching and commits) (60 minutes)
- integrating version control into your workflow (Git & GitHub via RStudio/Happy Git with R) (60 minutes)
- shareable compute environments (e.g., `renv`) (1.5 hrs) - link back to the second item
