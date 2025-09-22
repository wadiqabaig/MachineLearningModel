# NLP using NMF

This repository contains the implementation and report for an **unsupervised topic modelling** assignment exploring Twitter discussions of Netflix’s *Squid Game*.
The project applies **Non-negative Matrix Factorisation (NMF)** to TF-IDF representations to uncover latent themes in social media text.

---

## 📑 Contents
- `Report.pdf` – Full report with introduction, methodology, results, visualisations, and references.
- `src/` – Python scripts for preprocessing, model training, evaluation, and visualisation.
- `figures/` – Generated plots (intertopic map, hierarchical clustering, heatmaps, word clouds).

---

## ⚙️ Method Summary
- **Dataset:** [Squid Game Netflix Twitter Data](https://www.kaggle.com/datasets/deepcontractor/squid-game-netflix-twitter-data)
  – 30,000 English tweets randomly sampled for computational efficiency.
- **Preprocessing:** URL/hashtag removal, lower-casing, tokenisation, stopword removal, TF-IDF vectorisation.
- **Model:** `sklearn.decomposition.NMF` with grid-search tuning of
  `n_components` (8 topics optimum) and `l1_ratio`.
- **Evaluation:** C_v coherence (0.7684 best score).
- **Visualisation:** pyLDAvis intertopic maps, cosine-similarity heatmaps,
  top-term bar charts, and topic word clouds.

---
