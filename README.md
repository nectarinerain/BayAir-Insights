# Inbox Sentinel — From Baseline to Better: Spam/Ham Classifiers (Data 100 B1+B2)

A two-stage, end-to-end email spam detection project:
- **B1 (baseline):** build a first working spam/ham classifier and evaluate it.
- **B2 (improved):** strengthen the pipeline with **lemmatization**, **cross-validation**, **confusion matrix** diagnostics, and **GridSearchCV** for model selection/tuning.

This repo is organized for **recruiters and internship reviewers**: it shows a clean learning/iteration arc from a simple model to a better one, with transparent evaluation.

---

## 🧭 What each stage covers

### B1 — Baseline Spam/Ham Classifier
- **Goal:** Stand up a first model and evaluate it properly.
- **Modeling:** Logistic Regression (scikit-learn).
- **Evaluation:** ROC/AUC, precision/recall/F1 (intro metrics).
- **Outcome:** A working baseline with clear strengths/limitations documented inside the notebook.

### B2 — Improved Pipeline (Feature Engineering + Validation)
- **Goal:** Improve generalization and decision quality.
- **Preprocessing:** Tokenization pipeline with **lemmatization**.
- **Modeling & Selection:** **GridSearchCV** and **cross-validation**.
- **Diagnostics:** **Confusion matrix**, ROC/AUC, precision/recall/F1.
- **Outcome:** A more robust classifier with better-justified hyperparameters and validation.

> Notes: The notebooks contain code and markdown explaining each step. Results/figures (ROC, confusion matrix) are generated inside the notebooks.

---

## 🛠️ Tech Stack

- **Python**, **pandas**, **scikit-learn**
- **matplotlib / seaborn** (for plots, as used in B2)
- **NLTK / text preprocessing** (lemmatization in B2)
- Jupyter Notebooks (`.ipynb`)

---

## ▶️ How to Run

### 1) (Optional) Create environment
Using conda:
```bash
conda env create -f environment.yml
conda activate inbox-sentinel
