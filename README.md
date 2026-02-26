# RNA-seq Explorations (TCGA-BRCA)

## Project Overview
This project analyzes pseudo-RNA-seq count data derived from the TCGA-BRCA (breast cancer) cohort.  
The analysis focuses on the gene **TSPAN6** (ENSG00000000003.15) and explores its expression patterns across AJCC pathologic stages and vital status.

## Repository Contents
- `final_project.Rmd` – R Markdown file with full analysis code  
- `final_project_knit.pdf` – Knitted PDF output  
- `final_report.tex` – LaTeX report  

## Data Source
- **TCGA-BRCA: Breast Invasive Carcinoma RNA-seq counts and clinical metadata**  
  https://portal.gdc.cancer.gov/projects/TCGA-BRCA  
- Gene reference: **TSPAN6 (ENSG00000000003)** — [GeneCards page](https://www.genecards.org/cgi-bin/carddisp.pl?gene=TSPAN6)

## How to Reproduce
1. Open `final_project.Rmd` in RStudio.  
2. Adjust file paths if needed for `counts.csv` and `meta_data.csv`.  
3. Knit to PDF to generate plots and `sessionInfo()`.  
4. Compile `final_report.tex` in Overleaf or a local LaTeX environment.  

## Credits
R packages: `ggplot2`, `ComplexHeatmap`, `ggridges`.  
AI assistance: ChatGPT (OpenAI GPT-5) for editing and formatting guidance.
