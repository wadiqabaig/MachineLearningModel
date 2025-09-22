# Machine Learning Model
##
 Explainable Machine Learning on the Abalone Dataset

This repository explores **Explainable AI (XAI)** techniques—**SHAP** and **LIME**—to interpret
Logistic Regression and Random Forest models trained on the [UCI Abalone dataset](https://doi.org/10.24432/C55C7W).
It also includes a small-scale literature review of recent studies applying XAI methods in health,
cybersecurity, and software engineering.

---

## 📖 Contents
- `literature_review.pdf` – Complete report with introduction, methods, experimental results, and references.
- `src/` – Python scripts for preprocessing, training, and explainability analysis.
- `figures/` – Generated plots (SHAP summary, LIME beeswarm, etc.).
- `results/` – Accuracy and feature-importance metrics.

---

## ✨ Key Highlights
- **Logistic Regression + SHAP**  
  - Accuracy ~83–84%  
  - Global feature importance shows `Shell_weight` and `Shucked_weight` as dominant predictors.

- **Random Forest + LIME**  
  - Accuracy ~88–89%  
  - Local explanations reveal `Shell_weight` thresholds driving “Young” vs “Old” classification.

- Literature review compares XAI applications across:
  - **Healthcare** (dementia prediction, inflammatory bowel disease),
  - **Cybersecurity** (intrusion detection),
  - **Software Engineering** (fault detection).

---
