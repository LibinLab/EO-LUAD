# EO-LUAD
Scripts used for the analysis of single-cell and spatial transcriptomics data obtained from EO/LO-LUAD patients

## `samples_health_diseased_YO_sc_analysis_R`:
The code used to analyze scRNA, ST, TCGA and clinical data. 

- There are four parts in `samples_health_diseased_YO_sc_analysis_R.ipynb`.
  - `Samples_all_sc_analysis` part contains the code for scRNA and metadata analysis.
  - `TCGA_LUAD_Transcriptome` part contains the code for TCGA analysis.
  - `ICB_Response` part contains the code for ICB cohort analysis.
  - `All_8samples_st_analysis` part contains partial code for ST analysis.
  
## `8samples_young_lung_cancer_collection_st_analysis_python`:
The code used to analyze ST data. 

- There are four parts in `8samples_young_lung_cancer_collection_st_analysis_python`.
  - `TLS Region analysis` part contains the code for TLS regions visulization.
  - `CXCL13_T_B analysis` part contains the code for T, B cell subtypes visulization.
  - `Neighbor analysis` part contains the code for Neighbor fraction analysis.
  - `CCC analysis` part contains code for cell-cell interaction analysis in ST data.
 
## `CellPhoneDB_samples_healthy_diseased_YO_sc_analysis_python`:
The code used to analyze CellPhoneDB based cell-cell interactions in scRNA data. The code for visulization of CellPhoneDB results is in `samples_health_diseased_YO_sc_analysis_R`
