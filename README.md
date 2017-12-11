# rstudio_git_github_hpc

## workshop outline
***

### RSTUDIO -> local

#### Projects
- portability
- version control (git)
- pathways
- naming and filesystem conventions
- managing dependencies (packrat)

### Git
- clone
- pull
- push

###  Sharc

- file system
- data storage
    - ideally within the project (data are also version controlled) but not always possible
    - on sharc
    - on smb
    - on google drive
- unix for cluster basics
- the scheduler 
    - set up overview
    - brief overview of requesting resources
    - workflow basics
    - cluster etiquette
- R script submission bash script
    - load R and any external libraries
    - install first package interactively
    - if not using packrat, ensure your scripts include both `install.packages` and load (`library`) dependencies
- passing arguments to R scripts
- qsub


## What's the best way to keep your work on the cluster in sync?

### Github
- explain linking concepts
- workflow charts

### Git on the cluster
- same principles
- authentication issues


### General pitfalls of synching through github
- merge conflicts
    - branching (eg working with a master and devel branch)