## SSC 2022 Reproducibility workshop

Some definitions to help us scope the workshop:

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

- what is reproducibliily and why is it important (30-60 min)
- version control (e.g, Git & GitHub via RStudio/Happy Git with R) (3 hrs?)
- shareable compute environments (e.g., `renv`) (1.5 hrs)
