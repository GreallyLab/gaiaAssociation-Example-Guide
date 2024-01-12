# gaiaAssociation Example And Guide:

![alt text](https://github.com/samrosean/images/blob/main/logo_with_border_transparent.png)

****

Contained in this github repository are two of the three files you will need to replicate the gaiaAssociation analysis done within the gaiaAssociation paper. This test notebook and dataset were created to help teach new users and python beginners how to use gaiaAsscoiation (https://github.com/GreallyLab/gaiaAssociation) and RLEA analysis.

1. The example jupyter notebook which serves as a premade guide an explanatory tool for how to use gaiaAssociation within a jupyter notebook.

2. A zip file contining the .txt bed files for the 44 cell types ATAC-seq used in the gaiaAssociation paper.

The third and final piece you will need to replicate our analysis is a copy of the GWAS Cataolog (which can be procured here: https://www.ebi.ac.uk/gwas/docs/file-downloads). Our copy of the GWAS catalog (v1.0) was procured on 07/29/2023, so yours may be slightly different, but the GWAS catalog file is too large to include within a github project.



Extra files included in this repository to help show the functionality of gaiaAssociation are:

1. a .tsv file containing the names of the 18 specific studies used for the gaiaAssociation analysis, this file can be used to select which studies you wish gaiaAssociation to analyize out of the thousands of GWAS catalog studies. The usage of this is explained further within the example notebook

2. a .txt bed file for the Spark Genes (https://spark-sf.s3.amazonaws.com/SPARK_gene_list.pdf), a list of genes implicated in Autism which you can use as a mask to focus only on open chroamtin peaks which overlap with these particular genes. This file was not used in the gaiaAssociation analysis, but provides an example of how gaia can be used to combine open chromatin regions with other location data you want to further hone in on during a research question.

Also contained in this repository is the html version of the example notebook for less onerous viewing. 

## Author/Support

Samuel Rosean, samuel.rosean@einsteinmed.edu --- https://github.com/samrosean
