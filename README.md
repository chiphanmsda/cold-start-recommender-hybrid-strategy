# 🎯 Hybrid Cold-Start Recommender System

This project proposes a hybrid active learning approach to address the cold-start problem using error-based heuristics (Y-change + Error-change). The model is built on matrix factorization (SVD) and tested on implicit user-product interaction data.

## 🔍 Key Features
- Hybrid scoring strategy balances informativeness and error reduction
- Reproduced PopGini, random, Y-change, and Error-change baselines
- Binary rating dataset (De Bijenkorf, 70K interactions)
- Metric-driven evaluation using RMSE and Jaccard Index

## 🧪 Tools & Technologies
- Python, Surprise library (SVD)
- NumPy, Pandas
- Matplotlib for RMSE/accuracy plots

## 📊 Highlights
- Hybrid strategy outperformed random and PopGini in RMSE
- Demonstrated model drift resilience and early-item robustness
