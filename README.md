# 🧬 Optimized ctDNA Gene Panel for Early Detection of Triple-Negative Breast Cancer (TNBC)

> 🏆 **Award-Winning Project:** Winner of the **biotechnology.sy** Competition.

## 📌 Project Overview
This repository contains the bioinformatics pipeline and analysis code for designing an optimized, cost-effective, and highly sensitive targeted gene panel for early detection and Minimal Residual Disease (MRD) monitoring in Triple-Negative Breast Cancer (TNBC) using liquid biopsy (cfDNA/ctDNA). 

This project was developed under the expert supervision of **Dr. Joseph Shenkji, Ph.D. in Biotechnology Engineering**.

## 🎯 Key Features
- **Dynamic VAF Filtering:** Implements a smart window (0.0005–0.05) to capture ultra-low frequency tumor signals.
- **VIP Gene Rescue:** A pathogenicity-guided override rule to rescue critical low-VAF driver mutations (e.g., *TP53* L194F) that fail standard QC but are biologically validated.
- **Signal Purity Index (SPI):** A novel metric (0–3) to quantify the molecular cleanliness of each sample based on pathway complexity, max VAF, and driver ratio.
- **Dynamic Weighted Scoring:** An objective algorithm prioritizing genes based on early detectability, cohort recurrence, hotspot presence, and clinical relevance.
- **In Silico Panel Design:** Technical feasibility assessment (amplicon length, GC content, primer scoring) and hypothetical performance simulation (Sensitivity, Specificity, PPV).

## 📊 Final Prioritized Panel (5 Genes)
Based on the pipeline, the top 5 prioritized genes for the TNBC ctDNA panel are:
1. **TP53** (Score: 14.5)
2. **ERBB3** (Score: 8.5)
3. **KRAS** (Score: 8.5)
4. **NF1** (Score: 5.5)
5. **PIK3CA** (Score: 5.5)

## 🛠️ Repository Structure
- `data/`: Contains the curated relational tables (Clinical, Somatic Variants, CNVs, Pathways).
- `notebooks/`: Jupyter Notebook containing the full step-by-step bioinformatics pipeline.


## 📚 Data Source
Publicly available de-identified data from the **MSK Breast Cancer cfDNA (2026)** cohort via the [cBioPortal for Cancer Genomics](https://www.cbioportal.org) (Study ID: `breast_msk_cfdna_2026`).

## 👥 Project Team & Supervision
- **Researcher & Developer:** [Haya Nahhas](https://github.com/your-username) *(Independent Researcher in Bioinformatics, BSc in Bioengineering)*
- **Academic Supervisor:** **Dr. Joseph Shenkji**, Ph.D. in Biotechnology Engineering

## 📜 License
This project is intended for academic and research purposes. 
