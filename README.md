# Metabolomics 2019: Multi-Omics Integration and System Metabolomics

For this tutorial, we will be covering three workflows: 1) Metabolomics + Microbiome Data Integration, 2) Metabolomics + Transcriptomics Data Integration, and 3) Systems Metabolomics. Details for each workflow are below.

## 1) Metabolomics + Microbiome Data Integration

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/crc_data_june23.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of colorectal cancer (CRC) samples from a recent paper by [Yachida et al](https://www.nature.com/articles/s41591-019-0458-7). The data consists of shotgun metagenomic + targeted metabolomic analysis of fecal metabolome samples of 149 healthy subjects and 68 stage 3 or 4 CRC patients. 

First begin by performing shotgun data analysis to obtain a list of significantly enriched KOs [download ppt here](https://github.com/xia-lab/Metabolomics2019/blob/master/SDP_microbiomeanalyst.pptx). Then use MetaboAnalyst to identify the metabolomic CRC signnature [download ppt here](https://github.com/xia-lab/Metabolomics2019/blob/master/targeted_metabolomics_metaboanalyst.pptx). Finally, perform multi-omics data integration using the Network Explorer module within MetaboAnalyst.

## 2) Metabolomics + Transcriptomics Data Integration

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/breast_cancer.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of breast cancer samples from a paper by [Terunuma et al](https://www.ncbi.nlm.nih.gov/pubmed/24316975). The data consists of untargeted metabolomics (Metabolon) of 352 known metabolites and microarrary analysis (Affymetrix Human Gene 1.0 ST Array) of the tissue samples. Tissue samples were obtained from 67 human breast tumors and 65 tumor-adjacent noncancerous tissue samples.

To begin, perform microarray data analysis using NetworkAnalyst to obtain a list of enriched genes [download ppt here](). Next, use MetaboAnalyst to obtain the list of enriched metabolites [download ppt here](https://github.com/xia-lab/Metabolomics2019/blob/master/targeted_metabolomics_metaboanalyst.pptx). Note that though this pptx presents a different dataset, the same workflow can be applied to the breast cancer data.

## 3) Systems Metabolomics

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/ibd_data_june23.zip).

Follow [this tutorial]() to perform the System Metabolomics workflow.

## Additional Information

To explore individual Analyst's (i.e. MetaboAnalyst, MicrobiomeAnalyst and NetworkAnalyst) further, you can follow these protocols below. Do note that these are very comprehensive, providing detailed steps to use all available modules in the tool. 

### MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://www.dropbox.com/s/vsmcmvsup85h55u/CPBI_MetaboAnalyst_2019.pdf?dl=0)

### MicrobiomeAnalyst
[Using MicrobiomeAnalyst for comprehensive statistical, functional and meta-analysis of microbiome data](https://www.dropbox.com/s/025wp5p1aelc45f/MicrobiomeAnalyst_Nat_Prot_all_in_one.pdf?dl=0)

### NetworkAnalyst
[NetworkAnalyst for Statistical, Visual and Network-based Approaches for Meta-analysis of Expression Data](https://www.ncbi.nlm.nih.gov/pubmed/25950236)
