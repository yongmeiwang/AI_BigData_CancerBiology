
# Hands-On Activity 06  
## Mutation and Overall Survival in TCGA BRCA  
### Does Gene Mutation Impact Patient Survival?

In this activity, you will investigate whether mutation of a specific gene
is associated with overall survival (OS) in TCGA Breast Cancer patients.

You will construct Kaplan–Meier survival curves and interpret the results.
## Reference Example (Rendered HTML)

A sample Kaplan–Meier notebook is available here:

👉 https://yongmeiwang.github.io/AI_BigData_CancerBiology/Examples/TCGA_BRCA_Survival_KaplanMeier.html

Use this example to understand:
- How mutation status is defined
- How survival data are prepared
- How Kaplan–Meier curves are plotted

Do **not** copy code directly. Reproduce the logic independently.

---

## Learning Objectives

- Understand patient-level survival data
- Define mutation-positive vs mutation-negative groups
- Construct Kaplan–Meier survival curves
- Interpret survival differences critically
- Recognize the difference between sample-level and patient-level data

---

## Data Sources

Download from UCSC Xena (TCGA BRCA dataets ):

1. **MC3 mutation dataset**  
   mc3_BRCA_mc3.txt(Tumor-level mutation calls)

2. **TCGA BRCA clinical dataset**  
   survival_BRCA_survival.txt (Contains overall survival time and event status)

Place both files inside:1. **TCGA BRCA clinical dataset**  
   
Place both files inside:
data/
## Important Concept

TCGA mutation data are often sample-level.  
Survival data are patient-level.

Before merging datasets, ensure that you:
- Convert tumor sample barcodes to patient IDs (first 12 characters)
- Deduplicate survival records so each patient appears only once

---

## Your Task

### Part 1 — Define Mutation Status

1. Choose one frequently mutated gene (e.g., PIK3CA or TP53).
2. Identify patients harboring ≥1 nonsilent mutation in that gene.
3. Create a binary mutation status variable:
   - 1 = Mutated
   - 0 = Wild-type

---

### Part 2 — Prepare Survival Data

From the clinical dataset, extract:

- Overall survival time (OS.time)
- Overall survival event (OS)

Ensure:

- One row per patient
- No duplicate patient IDs

---

### Part 3 — Merge Mutation and Survival

Merge mutation status with survival data by patient ID.

Verify:
- Number of mutated patients
- Number of wild-type patients

---

### Part 4 — Kaplan–Meier Survival Analysis

1. Divide patients into:
   - Mutation-positive group
   - Mutation-negative group

2. Construct Kaplan–Meier survival curves.

3. (Optional) Perform a log-rank test.

Your plot should include:
- Clear title
- Axis labels
- Legend

---

## Interpretation

Write 6–10 sentences addressing:

- Do mutation-positive patients show different overall survival?
- Is the difference clinically meaningful?
- Does high mutation frequency imply survival impact?
- What confounding factors might influence results?
- Why might some driver mutations not alter overall survival?

---

## Submission

Submit:

- Your Jupyter notebook (.ipynb) or exported PDF
- Kaplan–Meier plot
- Number of patients in each group
- Interpretation paragraph