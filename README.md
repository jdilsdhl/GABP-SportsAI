📊 Sports Training Effect Analysis using GABP Neural Network & AI
This repository contains code, models, and supplementary materials for the research paper:

"Research on the Sports Training Effect Based on GABP Neural Network and Artificial Intelligence"

Published in IEEE Access
DOI: 10.1109/ACCESS.2024.0429000

📌 Overview
This project presents a hybrid Artificial Intelligence (AI) framework that integrates Genetic Algorithm-optimized Backpropagation (GABP) Neural Networks to evaluate and enhance sports training outcomes. By fusing AI-driven data analysis with adaptive modeling, the framework offers personalized training recommendations to improve athlete performance.

🚀 Key Features
⚙️ GABP Neural Network: Combines genetic algorithms with backpropagation to improve convergence and avoid local minima.
📈 AdaptFormer Architecture: A novel model to learn complex physiological adaptation dynamics.
📊 PIIE Module: Physio-Informed Inference Engine that integrates sports science priors (e.g., fatigue curves, injury risks).
⏱ Real-Time Feedback: Supports adaptive training updates through time-aware attention.
💡 Explainability: Enables interpretable training diagnostics (fatigue, adaptation, performance gain).
🧠 Model Components
Latent Embedding Transformation
Temporal Attention Memory
Personalized Output Decoding
Energy-Driven Latent Filtering
ACWR & Injury Risk Regularization
See detailed model diagram in Figure 1 and Figure 4 of the paper (pages 6 and 10).

📂 Datasets
🏃 TSSB Competition Dataset
🚦 UTSD Urban Traffic Dataset
🧠 TimeHetNet Temporal Graph Dataset
🛒 Amazon Sports Sequential Dataset
All datasets are publicly available and used under their respective licenses.

📊 Evaluation Metrics
MAE, RMSE, R², MAPE for time-series performance
NDCG@10, MRR@10 for sequential recommendation
Ablation studies and SOTA comparisons included (Tables 1–4, Figures 5–8)
🧪 Experimental Setup
Framework: PyTorch 1.13
Hardware: NVIDIA A100 80GB
Optimizer: Adam
Batch size: 64
Training epochs: 200 (early stopping with patience = 15)
