# EO-LUAD
Scripts used for the analysis of single-cell and spatial transcriptomics data obtained from EO/LO-LUAD patients

## `samples_health_diseased_YO_sc_analysis_v6_R_Revision`:
The code for integrated scRNA-seq data analysis and ST data preprocess

- There are three parts in `samples_health_diseased_YO_sc_analysis_v6_R_Revision.ipynb`.
  - `Samples_all_sc_analysis` part contains the code for integrated scRNA-seq data and sample metadata analysis.
  - `CellphoneDB` part contains the code for visualization of CellphoneDB results.
  - `All_8samples_st_analysis` part contains preprocess code for ST analysis.
  
## `8samples_young_lung_cancer_collection_st_analysis_v6_python_Revision`:
The code used to analyze ST data. 

- There are four parts in `8samples_young_lung_cancer_collection_st_analysis_python`.
  - `TLS Region analysis` part contains the code for TLS regions visulization.
  - `CXCL13_T_B analysis` part contains the code for T, B cell subtypes visulization.
  - `Neighbor analysis` part contains the code for Neighbor fraction analysis.
  - `CCC analysis` part contains code for cell-cell interaction analysis in ST data.
 
## `CellPhoneDB_samples_healthy_diseased_YO_sc_analysis_v6_python_Revision`:
The code used to analyze CellPhoneDB based cell-cell interactions in scRNA data. The code for visulization of CellPhoneDB results is in `samples_health_diseased_YO_sc_analysis_v6_R_Revision`

## `samples_YO_BulkRNA_analysis_v6_Revision`
The code for bulk RNA-seq validation dataset analysis

## `samples_YO_BulkRNA_mutation_integration_R_v6_Revision`
The code for somatic mutation and CNV analysis for EO-LUAD and driver gene.

## `samples_YO_ICBResponse_analysis_v6_Revision`
The code for ICB cohort analysis

## `samples_YO_MARSseqDataset_analysis_v6_Revision`
The code for scRNA-seq validation dataset analysis
