# # Hands-On Activity 04  
## From Visualization to Prediction  
### Logistic Regression with Integrin Expression

In this activity, you will move from exploratory visualization
to predictive modeling.

Your goal is to determine whether integrin gene expression
can distinguish Lung and Breast tissues.

This exercise follows a scientific reasoning workflow:
observe → hypothesize → test → evaluate → extend.

---

## Learning Objectives

- Connect visual patterns to predictive modeling
- Build logistic regression classifiers
- Interpret confusion matrices
- Evaluate model performance using accuracy and ROC curves
- Reflect on model robustness

---

## Dataset

Use the same dataset from Exercise 03:

data/gtex_tntegrin_7_organs.xlsx

---

## Reference Example

A rendered example notebook is available here:

👉 https://phoebe-miao.github.io/2025/07/17/Integrin-Genes-Model-Accuracy-Binary-Classification-ROC-Curves-Jupyter-Notebook.html

Use this as a structural reference only.  
Do not copy code directly.

---

# Your Task

## Part 1 — Visual Exploration

1. Create split violin plots (or similar distribution plots)
   comparing Lung vs Breast for multiple integrin genes.

2. Based on visual inspection:
   - Identify one integrin that appears to best separate the two tissues.
   - Identify one integrin that appears to poorly separate the two tissues.

Briefly justify your choices.

---

## Part 2 — Logistic Regression with a Strong Predictor

1. Use the integrin you believe best separates the tissues.
2. Build a logistic regression model using that single gene.
3. Use a 70/30 train-test split.
4. Evaluate:
   - Accuracy
   - Confusion matrix
   - ROC curve
   - AUC score

Interpret:
- Does the model perform as expected based on your visualization?


## Part 3 — Logistic Regression with a Weak Predictor

1. Use the integrin that appeared to poorly distinguish the tissues.
2. Build a logistic regression model using that single gene.
3. Use the same 70/30 split approach.
4. Evaluate:
   - Accuracy
   - Confusion matrix
   - ROC curve
   - AUC score

Interpret:
- How does performance compare to the strong predictor?
- What does this reveal about predictive signal strength?

---
---
# Part 4 — Model Stability (Binary Classification)

Repeat one of your binary models using a different `random_state`
in the train-test split.

Compare:
- Accuracy
- Confusion matrix
- AUC score

Discuss:
- Are the results stable?
- How sensitive is performance to the specific data split?
- What does this suggest about model reliability?

## Part 5 —  Multi-Class Logistic Regression (All 7 Organs)

Now extend the model beyond binary classification.

1. Use samples from all seven organs.
2. Select two integrin genes as features.
3. Train a logistic regression model to predict organ type.
4. Use a 70/30 train-test split.
5. Evaluate:
   - Accuracy
   - Confusion matrix (7 × 7)
   - Per-class performance patterns

Interpret:
- Which organs are most frequently confused?
- Why might certain tissues cluster together?
- Does adding more classes change model behavior?

---
## Reflection

1. How does binary classification differ from multi-class classification?
2. What does a confusion matrix reveal in multi-class settings?
3. Why might some tissues be harder to classify?
4. Does classification performance imply biological causation?

---

## Submission

Submit:

- Your notebook (.ipynb) or exported PDF
- Binary and multi-class confusion matrices
- ROC curves (for binary models)
- Accuracy values
- A short interpretation (6–10 sentences)