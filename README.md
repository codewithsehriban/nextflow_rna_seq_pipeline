# nextflow_rna_seq_pipeline
# RNA-seq Nextflow Web App

A Streamlit-based GUI for running an RNA-seq pipeline using Nextflow. Upload FASTQ files, provide genome index and annotation, and run the pipeline from your browser.

## Features
- FASTQ upload
- Run Trimming, QC, Alignment, and DE analysis
- HISAT2 + FeatureCounts + DESeq2

##Requirements
- Python 3.8+

- Nextflow installed

- Conda/Docker/Singularity (optional)
  
### ⬆️ 5. Push to GitHub

#### A. Initialize Git
cd rna-seq-nextflow-app/
git init
git add .
git commit -m "Initial commit: RNA-seq GUI with Streamlit and Nextflow"



## How to Use
pip install -r requirements.txt
streamlit run app.py

rna-seq-nextflow-app/
├── app.py                        # Streamlit GUI
├── nextflow_pipeline/
│   ├── main.nf                   # Your Nextflow pipeline script
│   └── nextflow.config           # Nextflow config
├── uploads/                      # Will hold uploaded FASTQ files (ignored by git)
├── results/                      # Will hold output (ignored by git)
├── .gitignore
├── requirements.txt              # Python packages
├── README.md                     # Description of your project

