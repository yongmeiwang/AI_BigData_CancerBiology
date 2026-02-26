# Hands-On Activity 05  
## TCGA BRCA: Identifying the Most Frequently Mutated Genes

In this activity, you will analyze somatic mutation data from
TCGA Breast Cancer (BRCA) and determine which genes are most
frequently mutated in this cohort.

This exercise introduces large-scale cancer genomics data
and reinforces concepts of frequency counting and interpretation.

---

## Learning Objectives

- Work with large mutation datasets
- Define mutation frequency clearly
- Rank genes by mutation frequency
- Generate a bar plot of top mutated genes
- Interpret biological meaning of mutation patterns

---
## Data Source

The mutation dataset used in this exercise is obtained from:

UCSC Xena Browser (TCGA hub)

Download the dataset here:

👉 https://xenabrowser.net/datapages/?dataset=mc3_gene_level%2FBRCA_mc3_gene_level.txt&host=https%3A%2F%2Ftcga.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443

Dataset name:
BRCA_mc3_gene_level.txt

This file contains gene-level mutation counts derived from the MC3
(Multi-Center Mutation Calling) TCGA dataset.
---

## File Placement

After downloading the file:

Place it inside the `data/` directory of this repository.

Example structure:

data/BRCA_mc3_gene_level.txt

Use a relative path when loading the file in your notebook.

## Reference Example

A rendered example notebook is available here:

👉 [TCGA BRCA Mutations Example](../Examples/TCGA_BRCA_Mutations.html)

Use this as a structural reference only.  
Do not copy code directly.

-----
## Your Task

### Part 1 — Identify Frequently Mutated Genes

Using the TCGA BRCA mutation dataset:

1. Determine how you will define mutation frequency.
   - Are you counting total mutation events?
   - Or number of tumors with ≥1 mutation in a gene?

2. Rank genes by mutation frequency.

3. Generate a bar plot showing the **Top 25 most frequently mutated genes**.

Your plot should clearly:
- Label axes
- Include a descriptive title
- Indicate what “frequency” represents

---

### Part 2 — Interpretation

Write 5–8 sentences addressing:

- Which genes appear at the top?
- Are these expected breast cancer driver genes?
- Why might very large genes appear frequently mutated?
- What are limitations of using raw mutation counts?

---

### Part 3 — Reflection

1. Does high mutation frequency imply functional importance?
2. What biases might affect mutation frequency ranking?
3. How might you refine this analysis to better identify driver genes?

---

## Submission

Submit:

- Your Jupyter notebook (.ipynb) or exported PDF
- Your Top 25 bar plot
- Your interpretation paragraph
