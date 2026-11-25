# Final Course Project: Metagenomic Analysis

Course Project 2 for Dr. Yanbin Yin's course, Fall 2026.

**Project Title: Microbiome Data Analysis of Zygnema Green Algae**

## Goals

1. Practice the genomics, bioinformatics, and computational skills learned in class.
2. Learn how to perform a complete metagenomic analysis using real sequencing data.
3. Understand the taxonomic composition, relative abundance, and functional potential of the Zygnema-associated microbiome.

## Steps Involved and Methods

1. **Data Preparation and Preprocessing** — FastQC and Trim Galore
2. **Removal of Host Reads** — Bowtie2 and SAMtools
3. **Metagenome Assembly** — MEGAHIT and metaSPAdes
4. **Binning and Bin Refinement** — MetaWRAP
5. **MAG Quality Assessment** — CheckM2
6. **Taxonomic Annotation** — GTDB-Tk
7. **MAG Abundance Analysis** — CoverM
8. **Gene Prediction and Functional Annotation** — DRAM

## Instructions

- Follow the PowerPoint slides and the provided protocol to complete each part of the project.
- All commands and SLURM scripts are provided in `protocol_final_project.txt`.
- The sequencing data are available on HCC.
- Update the file paths in the scripts to match your own working directory.
- Submit computationally intensive jobs using SLURM rather than running them directly on the login node.
- Check the output and error logs after each job.
- Include the required results and interpretations in your final report.
