# NCan-mice-tuberculosis
This repository contains the code corresponding to the publication: "Noncanonical T cell responses are associated with protection from tuberculosis in mice and humans" (JEM, 2025).

Abstract: While control of Mycobacterium tuberculosis (Mtb) infection is generally understood to require Th1 cells and IFNγ, infection produces a spectrum of immunological and pathological phenotypes in diverse human populations. By characterizing Mtb infection in mouse strains that model the genetic heterogeneity of an outbred population, we identified strains that control Mtb comparably to a standard IFNγ-dependent mouse model but with substantially lower lung IFNγ levels. We report that these mice have a significantly altered CD4 T cell profile that specifically lacks the terminal effector Th1 subset and that this phenotype is detectable before infection. These mice still require T cells to control bacterial burden but are less dependent on IFNγ signaling. Instead, noncanonical immune features such as Th17-like CD4 and γδT cells correlate with low bacterial burden. We find the same Th17 transcriptional programs are associated with resistance to Mtb infection in humans, implicating specific non-Th1 T cell responses as a common feature of Mtb control across species.

Last updated: 2025-04-16

This repository is administered by Christine Wiggins (daviscld@mit.edu)

Required Software:

R version 4.3.1

Required Packages:

liana_0.1.13        
DT_0.33             
wesanderson_0.3.7   
ggraph_2.2.1        
igraph_2.1.2       
corrr_0.4.4         
STRINGdb_2.12.1     
lsr_0.5.2           
caret_7.0-1         
lattice_0.22-6     
ropls_1.32.0        
systemsseRology_1.1 
limma_3.58.1        
Seurat_5.1.0        
SeuratObject_5.0.2 
sp_2.1-4            
pheatmap_1.0.12     
RColorBrewer_1.1-3  
viridis_0.6.5       
viridisLite_0.4.2  
ggrepel_0.9.6       
ggbeeswarm_0.7.2    
ggbreak_0.1.2       
ggExtra_0.10.1      
ggsignif_0.6.4     
summarytools_1.0.1  
openxlsx_4.2.7.1    
ggpubr_0.6.0        
lubridate_1.9.4     
forcats_1.0.0      
purrr_1.0.2         
tidyr_1.3.1         
tibble_3.2.1        
tidyverse_2.0.0     
gridExtra_2.3      
stringr_1.5.1       
readr_2.1.5         
readxl_1.4.3        
dplyr_1.1.4         
ggplot2_3.5.1      
COMPASS_1.38.1      
reshape2_1.4.4  

This is the tested environment, but program may run with other specifications.

Analysis was carried out under macOS Sonoma 14.2.1 with R run via R Studio Version 2023.06.1+524.

To generate any figures of interest, download the appropriate data from the Data folder, then run Load_functions.R followed by the appropriate R Markdown. Correspondence of markdowns to figures is as follows, with several additional intermediate figures generated per markdown:

Week_5_analysis.Rmd: Figure 3 PLSDA & blocked PCA, Figure 9, Figure S2A, Figure S5 A, B, & C

Week_2_analysis.Rmd: Figure S2 B, C, & D

Ligand_Receptor_Interactions.Rmd: Figure 6

COMPASS_plotting.Rmd: Figure 2 & Figure S1 COMPASS results

SELECT-seq_Translation.Rmd: Figure 10, Figure S5 TransCompR results

Baseline_analysis.Rmd: Figure 4 PLSDA, Figure S2 E & F
