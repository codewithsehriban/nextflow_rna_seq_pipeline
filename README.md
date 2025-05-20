# nextflow_rna_seq_pipeline
# RNA-seq Nextflow Web App

A Streamlit-based GUI for running an RNA-seq pipeline using Nextflow. Upload FASTQ files, provide genome index and annotation, and run the pipeline from your browser.

## Features
- FASTQ upload
- Run Trimming, QC, Alignment, and DE analysis
- HISAT2 + FeatureCounts + DESeq2

## How to Use

```bash
pip install -r requirements.txt
streamlit run app.py

