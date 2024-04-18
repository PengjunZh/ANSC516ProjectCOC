# ANSC516ProjectCOC

"COC_Metadata": metadata

The R scripts for alpha diversity, beta diversity, taxa (barplot and DEseq), co-occurrence are in the folder "R scripts/", each with an individual file:
  - "1-Alpha Diversity"
  - "2-Beta Diversity"
  - "3-Taxa (Barplots+DESeq2)"
  - "4-Cooccurrence"

The QIIME scripts were uploaded in the folder "QIIME pipeline/" in the following order:
  - "1-LogIn": Cluster Login and Module Load (Prep for Each Time)
  - "2-Upload+Import": Uploading Sequence & Metadata on Cluster and Importing Data to Qiime
  - "3-DADA2": Sequence Quality Control and Feature Table Construction
  - "4-Rarefaction": Phylogenetic Diversity Analyses Tree Generation and Alpha Rarefaction
  - "5-Diversity": Alpha and Beta Diversity
  - "6-Taxa": Taxa Bar Plots and ANCOM-BC
  - "7-RandomForest": Random Forest
