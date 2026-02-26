# Hands-On Activity 04  
## Logistic Regression and Model Evaluation  
### Can Integrin Expression Predict Tissue Type?

In this activity, you will build binary classification models
to distinguish **Lung** and **Breast** samples
based on integrin gene expression.

You will explore how model performance changes as you increase
the number of input features.

---

## Learning Objectives

- Understand logistic regression as a binary classifier
- Build models using one vs multiple gene features
- Interpret confusion matrices
- Evaluate model performance using accuracy and ROC curves
- Reflect on model limitations in biological data

---

## Dataset

Use the same dataset from Exercise 03:

data/gtex_integrin_7_organs.xlsx


---

## Reference Example

A rendered example notebook is available here:

👉 https://phoebe-miao.github.io/2025/07/17/Integrin-Genes-Model-Accuracy-Binary-Classification-ROC-Curves-Jupyter-Notebook.html

Use this as a structural reference only.  
Do not copy code directly.

---

## Your Task

### Part 1 — Single-Gene Logistic Regression

1. Select one integrin gene.
2. Use its expression value as the only feature.
3. Define binary labels:
   - Lung = 0
   - Breast = 1
4. Train a logistic regression classifier.
5. Evaluate:
   - Accuracy
   - Confusion matrix
   - ROC curve and AUC

Answer:
- How well does a single integrin separate Lung and Breast?

---

### Part 2 — Two-Gene Logistic Regression

1. Select two integrin genes.
2. Use both expression values as features.
3. Train a new logistic regression model.
4. Evaluate:
   - Accuracy
   - Confusion matrix
   - ROC curve and AUC

Compare results to the single-gene model.

Answer:
- Did performance improve?
- Why might adding features change model behavior?

---

### Part 3 — Reflection

1. What does the confusion matrix tell you that accuracy alone does not?
2. What biological interpretation can you make about integrin expression?
3. Does higher accuracy imply causal biological difference?
4. What are potential risks of overfitting in this setting?

---

## Submission

Submit:

- Your Jupyter notebook (.ipynb) or exported PDF
- Confusion matrices for both models
- ROC curves for both models
- Accuracy and AUC values
- A short discussion (5–8 sentences)

---

## Expectation

You are expected to:

- Decide how to construct feature matrices
- Implement logistic regression using scikit-learn
- Interpret model metrics critically
- Connect model results to biological reasoning
