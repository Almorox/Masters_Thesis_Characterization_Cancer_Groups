# Master’s Thesis “Characterization of genetically different groups of cancer patients using unsupervised methods.” (Master’s degree: Ciencia de Datos e Ingeniería de Computadores, UGR).  

* **Lucia_Almorox_TFM.pdf**: This file contains the thesis document.

* **Global_and_Bicluster_Specific_Analyses_CRC_Results.zip**: This file includes an Rmarkdown with supplementary material for the thesis. It provides the results obtained from all analyses conducted in the project. Due to the extensive nature of these results, only a small fraction is discussed in the thesis document.

* **Lucia_Almorox_TFM_defensa.pdf**: This file comprises the presentation slides for the defense of the thesis before an evaluation committee.

# Abstract
Patients’ genetic variability can significantly influence manifestations of colorectal cancer (CRC), resulting in a great heterogeneity of clinical symptoms. This project proposes to explore the performance of the PGMRA unsupervised algorithm on small datasets and evaluate its capacity to generate new knowledge. PGMRA was able to identify fuzzy biclusters (CRC patients x SNPs) based on genotypic data from patients with different diagnoses. The clinical profiles of the patients and the impact of the SNPs included in the CRC biclusters were extensively analyzed, utilizing a broad range of analytical and bioinformatic techniques. The analyses were performed on all patients together and compared to the biclusters’ results. The analysis of the entire sets of patients and SNPs uncovered the functional annotation of 695 affected genes, establishing direct relationships with CRC for 146 of them. Over-representation analyses identified terms related to neurological disorders in the total gene set and additional terms linked to calcium regulation in genes directly related to CRC. Both neurological disorders and hypercalcemia are known to be highly prevalent conditions in CRC. These prevalences could be originated by some of the genic SNPs that PGMRA utilized to group CRC patients. PGMRA biclusters arose interesting findings. Bicluster 16.12 included a small number of patients and genic SNPs, characterized by generally high MAFs (minor allele frequencies). Notably, this bicluster showed the lowest average age (44.25). The observed gene functions, related to inflammation and actin reorganization, point to classify its members with the CRC Consensus Molecular Subtype 4 (CMS4 - Mesenchymal). Additionally, these same CRC cases could be associated to Inflammatory Bowel Disease, explaining the low average age. We identified that AFF2 and PTCHD1-AS genes appeared frequently in different biclusters, affected by a high number of SNPs and remarkably high MAFs in some cases. These combinations varied across biclusters. Moreover, our RNA-Seq analysis, using external samples, identified both AFF2 and the target gene of PTCHD1-AS as underregulated genes in CRC. Thus, PGMRA results on small sample sizes showed to be able to find new insights into the complex interplay between genetic variants, clinical characteristics, and potential new perspectives on CRC subtypes, that must be experimentally tested in the laboratory.
