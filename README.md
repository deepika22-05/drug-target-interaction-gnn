# Drug-Target Interaction Prediction using GNN

A deep learning project that predicts drug-target interactions using Graph Neural Networks (GNN) on the DAVIS dataset.

## 🎯 Objective
Predict whether a drug molecule will bind to a target protein using GNN-based deep learning.

## 🧬 Dataset
- **DAVIS Dataset** — 68 drugs, 379 proteins, 30,056 interaction pairs
- Source: DeepPurpose library

## 🏗️ Model Architecture
- **Drug Encoder** — 3-layer GCN (Graph Convolutional Network)
- **Protein Encoder** — 2-layer MLP (amino acid sequence encoding)
- **Classifier** — Fully connected layers with dropout

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | 95.39% |
| AUROC | 0.5781 |
| F1 Score | 0.1042 |
| Strong Binding Recall | 89% |

## 🛠️ Tech Stack
- Python, PyTorch, PyTorch Geometric
- RDKit, DeepPurpose
- Google Colab (GPU)

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Results will be saved automatically

## 📁 Files
- `DTI_Day1.ipynb` — Main notebook with full pipeline
- `results.png` — Training and evaluation graphs

## 👤 Author
Deepika | Bioinformatics + Data Science
