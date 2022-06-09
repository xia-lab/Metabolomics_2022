# Metabolomics 2022: Spectra processing, functional integration and covariate adjustment of global metabolomics data using MetaboAnalyst 5.0

![alt text](https://github.com/xia-lab/Metabolomics2019/blob/master/metabolomics2022_xialab.png)

For this tutorial, we will be covering three workflows: 1) Optimized LC-MS spectra processing and peak annotation, 2) functional analysis and integration with other omics data, and 3) exploratory statistical analysis with complex metadata. Details for each workflow are below.

## 1) LC-MS Spectra Processing and Annotation ([Tutorial](https://dev.metaboanalyst.ca/resources/data/1_Raw%20Spectral%20Processing.pdf))

For this workflow, users could use the 2nd example or optionally download [here](https://www.dropbox.com/s/ift0zrkh0rx3v80/malaria_raw.zip?dl=0).

The aim of this workflow is use the **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to predict pathway-level activity from a subset of fecal metabolome samples from pediatric Crohn’s Disease (CD) patients. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in negative ion mode) of fecal samples from 24 pediatric CD patients and 24 healthy controls. Follow [this tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/systems_metabolomics_metaboanalyst.pptx) to perform the System Metabolomics workflow.

## 2) Functional Analysis and Integration ([Functional Analysis Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/SDP_microbiomeanalyst.pptx)) ([MetaboAnalyst Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/targeted_metabolomics_metaboanalyst.pptx)) ([OmicsNet Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/using_omicsnet.pptx))

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/crc_data_june23.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of colorectal cancer (CRC) samples from a recent paper by [Yachida et al](https://www.nature.com/articles/s41591-019-0458-7). The data consists of shotgun metagenomic + targeted metabolomic analysis of fecal metabolome samples of 149 healthy subjects and 68 Stage 3 or 4 CRC patients. 

First begin by performing shotgun data analysis in [MicrobiomeAnalyst](https://www.microbiomeanalyst.ca/) to obtain a list of significantly enriched KOs. Then use [MetaboAnalyst](https://www.metaboanalyst.ca/) to identify the metabolomic CRC signature. Finally, perform multi-omics data integration using the Network Explorer module within [MetaboAnalyst](https://www.metaboanalyst.ca/) or with [OmicsNet](https://www.omicsnet.ca/).

## 3) Metabolomics + Transcriptomics Data Integration ([NetworkAnalyst Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/transcriptomics_networkanalyst.pptx)) ([OmicsNet Tutorial](https://github.com/xia-lab/Metabolomics2019/blob/master/using_omicsnet.pptx))

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/breast_cancer.zip).

The aim of this workflow is to perform statistical analysis and data integration on a subset of breast cancer samples from a paper by [Terunuma et al](https://www.ncbi.nlm.nih.gov/pubmed/24316975). The data consists of untargeted metabolomics (Metabolon) of 352 known metabolites and microarrary analysis (Affymetrix Human Gene 1.0 ST Array) of the tissue samples. Tissue samples were obtained from 67 human breast tumors and 65 tumor-adjacent noncancerous tissue samples.

To begin, perform microarray data analysis using [NetworkAnalyst](https://www.networkanalyst.ca) to obtain a list of enriched genes. Next, use [MetaboAnalyst](https://www.metaboanalyst.ca/) to obtain the list of enriched metabolites. Note that though this pptx presents a different dataset, the same workflow can be applied to the breast cancer data. Finally, perform multi-omics data integration and 3D visualization using [OmicsNet](https://www.omicsnet.ca/).

## Additional Information

To explore individual Analyst's (i.e. MetaboAnalyst, MicrobiomeAnalyst, NetworkAnalyst and OmicsNet) further, you can follow these protocols below. Do note that these are very comprehensive, providing detailed steps to use all available modules in the tool. 

### MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://www.dropbox.com/s/vsmcmvsup85h55u/CPBI_MetaboAnalyst_2019.pdf?dl=0)

### MicrobiomeAnalyst
[Using MicrobiomeAnalyst for comprehensive statistical, functional and meta-analysis of microbiome data](https://www.dropbox.com/s/025wp5p1aelc45f/MicrobiomeAnalyst_Nat_Prot_all_in_one.pdf?dl=0)

### NetworkAnalyst
[NetworkAnalyst for Statistical, Visual and Network-based Approaches for Meta-analysis of Expression Data](https://www.ncbi.nlm.nih.gov/pubmed/25950236)

### OmicsNet
[Using OmicsNet for Network Integration and 3D Visualization](https://currentprotocols.onlinelibrary.wiley.com/doi/epdf/10.1002/cpbi.69)
