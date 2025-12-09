# Repository Overview

This repository contains the datasets, intermediate outputs, and analytical materials used in the study on multi-objective optimization (MOO) applications in biofuel research. The files support the bibliometric analysis, PRISMA-based screening workflow, topic classification procedure, and visualization of publication trends.

---

## Contents

### 1. Data and Screening Materials

- **scopus_export_all.csv**  
  Raw dataset exported from Scopus using the search query *“biofuel” AND “multi-objective optimization”*. Includes titles, abstracts, author keywords, document types, and publication years.

- **PRISMA_2020_flow_diagram_new_SRs_v1 (2).pdf**  
  PRISMA 2020 flow diagram documenting the identification, screening, exclusion steps, and final selection of studies used in the review.

- **classified_articles.xlsx**  
  Final dataset after LLM-based topic classification. Contains topic assignments for three thematic domains and model-generated rationales.

---

### 2. Bibliometric Statistics

- **Scopus-10-Analyze-Doctype.csv**  
  Document-type distribution extracted from Scopus analytics.

- **Scopus-10-Analyze-Year.csv**  
  Annual publication counts used to produce temporal trend plots.

- **Scopus-314-Analyze-Country.csv**  
  Country-level publication statistics used for geographical distribution analysis.

---

### 3. Visualizations

- **data_distribution_by_year.pdf**  
  Figure illustrating the annual trend in publications related to biofuel and MOO research.

---

### 4. Analysis Notebook

- **Data Statistics.ipynb**  
  Jupyter notebook containing preprocessing steps, descriptive statistics, visualization scripts, and code for generating summary charts included in the manuscript.

---

## Purpose

These materials provide transparency and reproducibility for the bibliometric and methodological analyses presented in the study, including dataset extraction, screening logic, topic classification, and statistical summaries.

