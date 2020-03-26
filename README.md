## Gastric Cancer Datasets

Repository containing code and data files relating to two Gastic Cancer genomic data sets.

**NB - the GSE62254 microarray data file was updated on 27 March 2020 (reprocessed using RMA with
no background correction).**

1. TCGA Stomach Cancer Data
    - Processed RNA-seq gene expression data from 415 gastric tumours, for 20502 genes.
    - Cancer Genome Atlas Research Network. (2014). Comprehensive molecular characterization of gastric adenocarcinoma. _Nature_, 513(7517), 202–209. http://doi.org/10.1038/nature13480
   
2. Gene Expression Omnibus (GEO) Gastric cancer data set (GEO ID: GSE62254)
    - Processed Illuima microarray gene expression data from 300 gastric tumours, for 20515 genes.
    - Cristescu, R., Lee, J., Nebozhyn, M., Kim, K.-M., Ting, J. C., Wong, S. S., et al. (2015). Molecular analysis of gastric cancer identifies subtypes associated with distinct clinical outcomes. _Nature Medicine_, 21(5), 449–456. http://doi.org/10.1038/nm.3850 
    
Directory organisation:

  - README.md: this file
  - Data: folder containing `.RData` versions of the two data sets
  - Code: basic R code to demonstrate how to load and explore the data in R

Within the `Code` directory, the file `gse62254_explore_data.R` contains some basic commands to load the GSE62254 data file, 
and begin some basic data exploration.  Within RStudio, the "Compile Report" functionality can be used to run the code and generate the following basic markdown output:

[Report: gse62254_explore_data.R](Code/gse62254_explore_data.md)
