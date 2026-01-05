# DNA-based NGS Data Analysis

This repository provides an overview of the **different types of DNA-based Next-Generation Sequencing (NGS) analyses** that can be performed, depending on the biological or clinical question.

---

## 1. Whole Genome Sequencing (WGS)

**Description:**  
Analyzes the complete DNA sequence of an organism.

**Key Analyses:**
- SNP and INDEL detection
- Structural variant detection
- Copy number variation (CNV)
- Population genetics
- Disease-associated mutations

**Applications:**
- Rare disease diagnosis  
- Cancer genomics  
- Evolutionary studies  

---

## 2. Whole Exome Sequencing (WES)

**Description:**  
Focuses on protein-coding regions (exons), ~1–2% of the genome.

**Key Analyses:**
- Gene mutation discovery
- Mendelian disease studies
- Variant prioritization

**Advantages:**
- Lower cost than WGS
- Easier interpretation

---

## 3. Targeted DNA Sequencing

**Description:**  
Sequences predefined genes or genomic regions.

**Key Analyses:**
- Known mutation screening
- Clinical diagnostics
- Validation of variants

**Examples:**
- Cancer gene panels
- Pharmacogenomics panels

---

## 4. Variant Calling & Genotyping

**Description:**  
Core analysis for identifying DNA sequence differences.

**Detects:**
- SNPs
- INDELs
- CNVs
- Structural variants (SVs)

**Downstream Uses:**
- Pathogenicity prediction
- Precision medicine
- Genotype–phenotype association

---

## 5. Metagenomics

**Description:**  
Analyzes DNA from mixed microbial communities.

**Key Analyses:**
- Species identification
- Taxonomic profiling
- Functional annotation

**Applications:**
- Microbiome studies
- Environmental DNA (eDNA)
- Pathogen detection

---

## 6. Comparative Genomics

**Description:**  
Compares genomes across individuals or species.

**Key Analyses:**
- Genome alignment
- Conserved region identification
- Evolutionary inference

---

## 7. Epigenomics (DNA-based)

**Description:**  
Studies chemical modifications on DNA rather than sequence changes.

**Key Analyses:**
- DNA methylation analysis (e.g., bisulfite sequencing)
- Regulatory region mapping
- Gene regulation studies

**Note:**  
Epigenetic changes affect gene expression, not DNA sequence.

---

## 8. Copy Number Variation (CNV) Analysis

**Description:**  
Identifies duplicated or deleted DNA regions.

**Applications:**
- Cancer genomics
- Developmental disorders
- Neurological disease studies

---

## 9. Structural Variant Analysis

**Description:**  
Detects large-scale genomic rearrangements.

**Examples:**
- Inversions
- Translocations
- Large insertions/deletions

**Importance:**
- Cancer research
- Genetic syndromes

---

## 10. Population & Evolutionary Genetics

**Description:**  
Analyzes genetic variation within and between populations.

**Key Analyses:**
- Genetic diversity
- Natural selection
- Phylogenetics
- Ancestry inference

---

## 11. Quality Control & Preprocessing (Essential Step)

**Purpose:**  
Ensures reliability of downstream analyses.

**Common Steps:**
- Read quality assessment
- Adapter trimming
- Coverage analysis
- Alignment quality checks

---

## Typical DNA-NGS Analysis Pipeline

1. Raw sequencing reads (FASTQ)
2. Quality control
3. Read trimming and filtering
4. Alignment to reference genome
5. Variant calling
6. Variant annotation
7. Biological interpretation

---

## Summary

DNA-based NGS enables a wide range of analyses from basic variant detection to complex population and epigenetic studies. The choice of analysis depends on the research or clinical objective.

---

## License

This repository is intended for educational and research purposes.
