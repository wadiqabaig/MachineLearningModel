# Machine Learning Model Collection

This repository hosts two independent **Machine Learning** projects developed for
academic coursework and personal exploration.  
Each folder contains its own dataset, source code, and report.

---

## 📂 Project 1 – LR & RF with XAI (Abalone Age)

**Goal:**  
Predict the age category of abalone shells using **Logistic Regression** and **Random Forest**,  
Then explain model decisions with **Explainable AI (XAI)** techniques.

**Highlights**
- Dataset: [UCI Abalone](https://doi.org/10.24432/C55C7W)
- Methods: Logistic Regression & Random Forest
- Explainability: **SHAP** and **LIME** for global & local feature importance
- Results: Random Forest achieved ~89% accuracy; key predictors include `Shell_weight` and `Shucked_weight`.

---

## 📂 Project 2 – NLP with NMF (Twitter Topic Modelling)

**Goal:**  
Uncover latent discussion topics from *Squid Game* Twitter data using  
**Non-negative Matrix Factorisation (NMF)** on TF-IDF vectors.

**Highlights**
- Dataset: [Squid Game Netflix Twitter Data](https://www.kaggle.com/datasets/deepcontractor/squid-game-netflix-twitter-data)
- Preprocessing: Cleaning, tokenisation, stopword removal, TF-IDF
- Model Tuning: Grid search on `n_components` and `l1_ratio`
- Evaluation: Coherence score (C_v) – best score ≈ **0.7684** with 8 topics
- Visualisations: Intertopic maps, similarity heatmaps, top-term bar charts, word clouds

---

## 🛠️ Setup (General)
Both projects use Python 3.9+.

```bash
Download the python file and run using Google Colab.
