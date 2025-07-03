# CMG-Project
This project was conducted as part of the Computational and Microbial Genomics course at the Università degli Studi di Trento
This study investigates the genomic characteristics and evolutionary history of a specific Species-level Genome Bin (SGB3588) identified in the human oral cavity microbiome. The study focuses on analyzing Metagenome-Assembled Genomes (MAGs) obtained from individuals with dental implants who presented with varying clinical conditions: healthy control, mucositis, and peri-implantitis. Using integrated pangenomic and phylogenetic approaches, the research aimed to characterize the pangenome structure of SGB3588 strains, understand their phylogenetic relationships, and explore potential links between genomic variation and disease states.

## Authors

*   Sofia Pietrini
*   Anna Salsano
*   Caterina Sanetti

Affiliation: Department of Cellular, Computational and Integrative Biology, Universit`a degli Studi di Trento

## Date

06/04/2025

## Key Research Areas

*   Oral Microbiome Analysis
*   Metagenome-Assembled Genomes (MAGs)
*   Species-level Genome Bin (SGB3588) Characterization
*   Bacterial Pangenomics (Core and Accessory Genomes)
*   Phylogenetic Reconstruction
*   Association with Peri-implant Diseases (Mucositis, Peri-implantitis)
*   Genome Annotation and Functional Prediction

## Data

The study utilized a dataset of 30 MAGs classified under SGB3588, originating from the oral cavity of patients with dental implants. Associated metadata included patient age, smoking status, and clinical diagnosis.

## Methods Summary

The analysis pipeline involved several key steps:

1.  **Quality Control:** MAG quality assessment using CheckM.
2.  **Taxonomic Assignment:** Refinement of taxonomic classification using PhyloPhlAn against the MetaRefSGB database.
3.  **Genome Annotation:** Annotation of protein-coding sequences and other genomic features using Prokka.
4.  **Pangenome Analysis:** Construction and analysis of the SGB3588 pangenome (identifying core, shell, and cloud genes) using Roary.
5.  **Phylogenetic Analysis:** Reconstruction of maximum-likelihood phylogenetic trees based on core gene alignments (FastTreeMP) and accessory gene presence/absence, visualized with iTOL and GraPhlAn incorporating metadata.

## Key Findings

*   Initial quality filtering led to the exclusion of 4 low-quality MAGs. No strong association was found between MAG quality and patient metadata.
*   Taxonomic assignment confirmed the MAGs belong to the *Treponema* genus within the Treponemataceae family, consistent with an oral origin.
*   Genome annotation revealed a substantial proportion of hypothetical proteins (~50%), suggesting novel gene content within this SGB.
*   Pangenome analysis indicated an *open* pangenome structure for SGB3588, characterized by a relatively small core genome (~13.5%) and a large proportion of accessory/cloud genes (total 7007 gene clusters).
*   Functional analysis of accessory genes identified potential roles related to sugar transport, antibiotic resistance (e.g., MepA), and metabolic regulation (e.g., urocanate reductase).
*   Phylogenetic trees (based on both core and accessory genes) did *not* show strong, consistent clustering of strains based on clinical status, smoking status, or sex across the entire dataset. Some small clusters with shared clinical origin were observed, but the limited sample size likely constrained the ability to detect significant associations.

## Conclusion

The SGB3588 population studied exhibits an open pangenome structure with a substantial proportion of novel genes. While functional analysis highlighted potentially relevant accessory genes, the study's limited sample size restricted the power to identify robust associations between genomic features or phylogenetic clustering and peri-implant health or disease states. Larger future studies are needed to further explore these potential links.

## Main Software/Tools Used

*   CheckM
*   PhyloPhlAn
*   Prokka
*   Roary
*   FastTreeMP
*   iTOL
*   GraPhlAn
