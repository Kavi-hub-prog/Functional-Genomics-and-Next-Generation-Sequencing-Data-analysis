# NGS Variant Analysis Pipeline (WES Data)

## 📌 Project Overview
This project demonstrates a complete bioinformatics pipeline for analyzing Whole Exome Sequencing (WES) data, including quality control, alignment, variant calling, and variant annotation.

## 🧬 Objectives
- Process raw sequencing data (FASTQ)
- Perform alignment to the human reference genome (GRCh38)
- Identify genetic variants (SNPs/INDELs)
- Annotate variants for biological significance

## ⚙️ Tools & Technologies
- SRA Toolkit (data download)
- FastQC (quality control)
- Bowtie2 (alignment)
- Samtools (BAM processing)
- Bcftools (variant calling)
- SnpEff (variant annotation)
- Linux (WSL environment)

## 📊 Workflow
1. Download WES dataset from NCBI SRA
2. Convert SRA → FASTQ (fasterq-dump)
3. Perform quality check using FastQC
4. Align reads to GRCh38 reference genome using Bowtie2
5. Convert SAM → BAM, sort and index (Samtools)
6. Mark duplicates and filter reads
7. Perform variant calling using Bcftools
8. Annotate variants using SnpEff

## 📈 Results
- Generated VCF file (~7.3 MB) containing genetic variants
- Annotated ~70,000+ variants
- Classified variants into:
  - High impact: ~0.33%
  - Moderate impact: ~11%
  - Low impact: ~4%
  - Modifier: ~84%

## 🚀 Key Learnings
- Hands-on experience with NGS data analysis pipeline
- Understanding of genomic data formats (FASTQ, BAM, VCF)
- Practical exposure to variant interpretation

## 👩‍💻 Author
Kavita Krishna Panwar
