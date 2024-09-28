# Transcriptional profiling of patients with Fuchs endothelial corneal dystrophy with and without trinucleotide repeat expansion in TCF4


## Overview

This repository contains the analysis pipeline for transcriptional profiling of corneal endothelial cells obtained from patients with Fuchs endothelial corneal dystrophy (FECD), comparing those with and without trinucleotide repeat expansion in the TCF4 gene.

---

## Contents

| File | Description |
|------|-------------|
| `DESeq2_gene_analysis.R` | Main script for differential gene expression analysis |
| `Sample_List_YYYYMMDD.txt` | Sample information file |
| `DataMatrix_YYYYMMDD.txt` | Gene expression data matrix |
| `DESeq2_Result_of_WaldTest_Case_vs_Control.txt` | Results of differential expression analysis |

---

### Example of Table Format of Sample_List_YYYYMMDD.txt
"SRRXXXXXXXX.genes.results" files were obtained by RSEM

|  sample  | group |  RIN  | path |
|----------|-------|-------|------|
| Case1  | case  | 6.3   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |
| Case2  | case  | 8.0   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |
| Case3  | case  | 7.3   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |
| Control1 | ctr | 7.4   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |
| Control2 | ctr | 8.0   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |
| Control3 | ctr | 7.2   | /path/to/your/working/directory/SRRXXXXXXXX.genes.results |

---

## Requirements

- R version 4.3.2
- DESeq2 package
- tximport package

---

## Usage

1. Clone this repository
2. Set the working directory in `DESeq2_gene_analysis.R`
3. Ensure all required input files are present
4. Run the R script

---

## Acquisition of RNA-Seq Data

Raw fastq files of CECs derived from non-FECD and FECD subjects were obtained from the DNA Data Bank of Japan (DDBJ) Sequence Read Archive (SRA) under the accession IDs [DRP006678] and [DRA015078], respectively.

---

## Citation

If you use this code or data, please cite our paper:

```
[Citation information]
```

---

## Contact

For questions or issues, please contact:

**Tatsuya Nakagawa**  
Email: tatsuya.n.nakagawa@gmail.com
