# AI and Big Data in Cancer Biology

An introduction to big data in cancer biology and data-driven analysis using artificial intelligence

## 🎯 Course Vision

Modern cancer research has entered an era dominated by large-scale genomic, transcriptomic, and clinical datasets. Yet many trainees—from high school students to undergraduate researchers and laboratory-based scientists—lack exposure to the breadth of available data resources and the analytical frameworks required to extract biological insight. Without this foundation, the potential of public cancer datasets to inform hypothesis generation and experimental validation remains underutilized. This course is designed to provide a conceptual and practical bridge between biological experimentation and data-driven discovery.

This course does not assume you have any coding experience. You can start from scratch zero, but will learn to use AI to help you code and interpret biomedical data.

This course will introduce students to:
- The historical development of “big data” in cancer biology
- Genomic and transcriptomic datasets (TCGA, GTEx, etc.)
- Basic RNA-seq data interpretation
- Survival analysis and clinical associations
- Introductory machine learning concepts applied to cancer datasets

---

## 📂 Repository Structure

The repository is organized into modular components:

- `Lectures/` – lecture materials and notebooks  
- `Exercises/` – computational assignments  
- `Data/` – teaching datasets  
- `Examples/` – Rendered html of Jupyter Notebook Examples 
- `docs/` – future course website

Lecture slides are provided in PDF format. In-class activities are implemented as Jupyter notebooks under the `Exercises/` directory.
Teaching datasets included in this repository are derived from publicly available open-access resources (e.g., GTEx, TCGA, CCLE).

## Hands-On Exercises

In Exercises Folders, we provide 6 progressive computational workflow.

### Exercise 01 — Establishing Your Scientific Web Presence
Create a personal GitHub Pages website and understand how open scientific communication works.

### Exercise 02 — Launching Jupyter and Exploring Basic Plotting
Install Jupyter Notebook, learn basic terminal commands, and generate simple math plots.

### Exercise 03 — Gene Expression Analysis with Pandas (GTEx)
Introduce structured data manipulation using **pandas**:
- Load Excel files
- Filter and subset data
- Compute summary statistics
- Generate violin/box plots
- Interpret tissue-specific gene expression

### Exercise 04 — Logistic Regression and Model Evaluation
Use integrin expression to classify tissues.
Explore:
- Single-gene prediction
- Multi-gene prediction
- Confusion matrix
- ROC curves
- Model stability

### Exercise 05 — Mutation Frequency in TCGA BRCA
Identify the most frequently mutated genes in breast cancer using TCGA mutation data.

### Exercise 06 — Mutation and Patient Survival
Investigate whether mutation of specific genes impacts overall survival in TCGA BRCA using Kaplan–Meier analysis.

---

## Rendered Example Notebooks

Rendered HTML notebooks are available via GitHub Pages:

- Basic Matplotlib Example  
  👉 https://yongmeiwang.github.io/AI_BigData_CancerBiology/Examples/matplotlib_functions.html

- TCGA BRCA Mutation Analysis  
  👉 https://yongmeiwang.github.io/AI_BigData_CancerBiology/Examples/TCGA_BRCA_Mutations.html

- Kaplan–Meier Survival Analysis  
  👉 https://yongmeiwang.github.io/AI_BigData_CancerBiology/Examples/06_survival_mutation.html

