# Orchestrating Single-Cell Analysis with Bioconductor: Workshop Edition

# Instructors names and contact information:

* Robert A. Amezquita, robert.amezquita@fredhutch.org
* Stephanie C. Hicks, shicks19@jhu.edu

# Workshop Description

This workshop gives an introductory overview of analyzing single-cell data, particularly RNA-seq, using Bioconductor software. This workshop will help participants to understand essential Bioconductor infrastructure, such as the *SingleCellExperiment* class, and various analytical routines using real-world data. Finally, this workshop is modeled after the manuscript *"Orchestrating Single-Cell Analysis with Bioconductor"* (Amezquita et al. 2019). Students will analyze provided example datasets on their personal laptop. This workshop will be a mixture of example code shown by instructors (available through this repository) and short exercises.


## Pre-requisites

* Basic knowledge of R syntax
* Some familiarity with S4 objects may be helpful, but is not required
* Some familiarity with tidyverse syntax and methods, such as the usage of pipes, may be helpful, but is not required
* Familiarity with high-throughput gene expression data as obtained from RNA-seq

Relevant background reading:

* [Amezquita, R. A. et al. Orchestrating Single-Cell Analysis with Bioconductor. 14, e1006378–32 (2019).](https://www.biorxiv.org/content/10.1101/590562v1)


## Workshop Participation

Students will be able to run code interactively during the workshop on their personal computers during a live demonstration of the code used herein, with ample opportunity for questions, answers, and discussion.


## _R_ / _Bioconductor_ packages used

* [SingleCellExperiment](https://bioconductor.org/packages/SingleCellExperiment)
* [scater](https://bioconductor.org/packages/scater)
* [TENxPBMCData](https://bioconductor.org/packages/TENxPBMCData)
* [DropletUtils](https://bioconductor.org/packages/DropletUtils))
* [scater](https://bioconductor.org/packages/scater)
* [scran](https://bioconductor.org/packages/scran)
* [igraph](https://igraph.org/r/)
* [devtools](https://github.com/r-lib/devtools)
* [tidyr](https://tidyr.tidyverse.org)
* [tensorflow](https://tensorflow.rstudio.com)
* [cellassign](https://github.com/Irrationone/cellassign)


## Time outline

50 min workshop consisting of the following:

| Activity                                        | Time |
|-------------------------------------------------|------|
| Introduction to Workshop                        |   5m |
| Infrastructure: the SingleCellExperiment class  |  10m |
| Framework of Single-Cell RNA-seq analysis       |  10m |
| Data processing (QC, Norm, Feature Selection)   |  10m |
| Downstream: Clustering, DE, Annotation          |  10m |
| Sharing Data: Interactive Analysis              |   5m |


# Workshop Goals and Objectives

## Learning goals

* Describe the framework needed to implement a basic single-cell RNA-seq analysis
* Describe the utility and design of the *SingleCellExperiment* object in the context of the analysis framework
* Identify critical steps within a typical single-cell RNA-seq analysis that can greatly influence end-results
* Understand the differences between single-cell vs. bulk based technologies, and the advantages/disadvantages of each


## Learning objectives

* Import single-cell RNA-seq data from raw counts into a *SingleCellExperiment* object
* Utilize the *SingleCellExperiment* object for annotation, subsetting, and processing via ad-hoc and established methods
* Produce descriptive plots from *SingleCellExperiment* objects to evaluate key quality control and processing steps
