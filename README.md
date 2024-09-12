# gaiaAssociation Example And Guide:

![alt text](https://github.com/samrosean/images/blob/main/logo_with_border_transparent.png)

****

View this example notebook in a google colab workspace [here!](https://colab.research.google.com/drive/1AkKWNDi9E9gCcvRiKSQKTp8GN_qGYWJY?usp=sharing).

This test notebook and dataset were created to help teach new users and python beginners how to use gaiaAsscoiation (https://github.com/GreallyLab/gaiaAssociation) and perform RLEA analysis. Contained in this github repository are two of the three files you will need to replicate the analysis done within the gaiaAssociation paper:

1. The example jupyter notebook which serves as a premade guide and explanatory tool for how to use gaiaAssociation within a jupyter notebook.

2. A zip file contining the .txt bed files for the 44 cell types of ATAC-seq data used in the gaiaAssociation paper.

The third and final piece you will need to replicate our analysis is a copy of the GWAS Cataolog (which can be procured here: https://www.ebi.ac.uk/gwas/docs/file-downloads). Our copy of the GWAS catalog (v1.0) was procured on 07/29/2023, so your version may be slightly different, but the GWAS catalog file is too large to include within a github project.



Extra files included in this repository to help show the diverse functionality of gaiaAssociation are:

1. A folder (atlas_peaks) which contains ATAC-seq peak BED files in .txt format for 222 cell types, including both adult and fetal cell types, identified in the paper 'A single-cell atlas of chromatin accessibility in the human genome by Zhang et al. (2021)' (PMC: 8664161). This provides perhaps the best set of cell types to reference with gaiaAssociation, and is the recommended group of ATAC bed files to use, though they were brought together for this use after the publication of the gaiaAssociation paper. The snATAC-seq reads were all aligned to reference genome GRCh38. The additional cell types provide a broader atlas of chromatin accessibility across cells found in over 40 tissue types, enhancing the ability to identify GWAS variant enrichment in regulatory loci mediated by different cell types. The data has been formated for use by gaiaAssociation including the proper column IDs: “Chromosome,” “Start,” and “End”.

2. a .csv file containing the names of the 18 specific studies used for the gaiaAssociation analysis, this file can be used to select which studies you wish gaiaAssociation to analyize out of the thousands of incuded GWAS catalog studies. The usage of this is explained upon further within the example notebook

3. a .txt bed file for the Spark Genes set (https://spark-sf.s3.amazonaws.com/SPARK_gene_list.pdf), a list of genes implicated in Autism which you can use as a mask to focus only on open chroamtin peaks which overlap with these particular genes. This file was not used in the gaiaAssociation analysis, but provides an example of how gaia can be used to combine open chromatin regions with other location data you want to further hone in on during a research question.

Also contained in this repository is the html version of the example notebook for less onerous viewing. 

## Author/Support

Samuel Rosean, samuel.rosean@einsteinmed.edu --- https://github.com/samrosean
