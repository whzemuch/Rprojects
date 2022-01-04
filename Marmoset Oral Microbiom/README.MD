## Data
  - **Type**: 16s V4 amplicon sequencing data
  - **Source**: marmoset gingival tissue


## Packages for data analysis
### DADA2: Bioconductor Workflow for Microbiome Data Analysis: from raw reads to community analyses 
  
  - Ben J. Callahan1, Kris Sankaran1, Julia A. Fukuyama1, Paul J. McMurdie2, Susan P. Holmes1
      Author details
      1 Statistics Department, Stanford University, Stanford, CA, 94305, USA
      2 Whole Biome Inc., San Francisco, CA, 94107, USA

  - https://f1000research.com/articles/5-1492/v2
  - github: https://github.com/spholmes/F1000_workflow


### MicrobiotaProcess

MicrobiotaProcess is an R package for analysis, visualization and biomarker discovery of microbial datasets. It introduces MPSE class, this make it more interoperable with the existing computing ecosystem. Moreover, it introduces a tidy microbiome data structure paradigm and analysis grammar. It provides a wide variety of microbiome analsys procedures under the unified and common framework (tidy-like framework).

  - Xu S, Yu G (2021). MicrobiotaProcess: an R package for analysis, visualization and biomarker discovery of microbiome. R package version 1.6.3, 
  - https://github.com/YuLab-SMU/MicrobiotaProcess/.
  - Installation
     To install this package, start R (version "4.1") and enter:

    if (!requireNamespace("BiocManager", quietly = TRUE))
        install.packages("BiocManager")
    
    BiocManager::install("MicrobiotaProcess")
