# Hands-On Activity 03  
## GTEx Integrin Expression: Lung vs Breast (Jupyter Notebook)

In this activity, you will use a curated GTEx-derived dataset to compare **integrin gene expression** between **Lung** and **Breast** tissues using Jupyter Notebook


This exercise is intentionally less guided.
You are expected to explore the dataset and construct your own analysis workflow, and learning to use python coding more. You may use ChatGPT or Gemini to help you learn the coding. 

You will practice:
- loading an Excel file with pandas
- filtering a dataframe
- reshaping data for plotting
- creating distribution plots
- interpreting results

---

## Learning Objectives

By completing this activity, you will be able to:

- Load and inspect a real biological dataset in pandas
- Filter data by tissue type (Lung vs Breast)
- Visualize distributions of gene expression using plots
- Summarize and interpret differences between tissues

---

## Dataset

You are provided:

Gtex_integrin_7_organ.xlsx

The file is currently located under directory "data/" folder.

Place the file in your working directory or a `data/` folder.


---

## Reference Example

A rendered example notebook is available here:

👉 https://phoebe-miao.github.io/2025/07/15/Gene-Expression-of-Integrins-Jupyter-Notebook.html

Use this as a structural reference only.  
Do not copy code directly.
## Important Note About File Paths

The reference example notebook uses a full local path (e.g., `C:\Users\...`).

You should **NOT** hard-code your personal computer’s absolute file path.

Instead, use a **relative path**, such as:

- `"Gtex_integrin_7_organ.xlsx"`  
- `"data/Gtex_integrin_7_organ.xlsx"`

Relative paths make your notebook portable and reproducible.
Your code should work on another computer without modification.

This is an important practice in computational research.

## Your Task

Create a new Jupyter notebook and perform the following:

1. Load the dataset.
2. Identify the relevant columns (tissue, gene, expression).
3. Subset the data for:
   - Lung
   - Breast
4. Generate at least one distribution plot comparing Lung vs Breast.
5. Select one integrin gene and compare its expression between tissues.
6. Provide brief biological interpretation (3–5 sentences).

You may choose your own plotting style (boxplot, violin plot, etc.).
---

## Submission

Submit:
- Your Jupyter notebook (.ipynb) or exported PDF
- Your plots
- Your interpretation

---

## Expectation

You are expected to:

- Inspect column names yourself
- Decide how to reshape/filter data
- Choose appropriate visualization methods
- Debug your own errors
