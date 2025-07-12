<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/he/thumb/7/7e/Technion_logo.svg/512px-Technion_logo.svg.png" alt="Technion Logo" width="120"/>
</p>

<h1 align="center">🧠 LaCC Project</h1>
<p align="center">
  <em>Language, Computation and Cognition</em><br>
  Decoding semantic meaning from brain activity using fMRI and word embeddings
</p>

---

## 📘 Project Summary

This notebook explores how linguistic meaning can be decoded from human brain activity using functional MRI (fMRI) and modern semantic embedding models. It replicates and extends the experiments of [Pereira et al. (2018)](https://www.nature.com/articles/s41467-018-03068-4), comparing:

- Static embeddings (GloVe, Word2Vec)
- Contextual embeddings (BERT)
- Brain **decoder** and **encoder** models
- Inter-subject generalization paradigms

All results, visualizations, and evaluations are contained in a single notebook:  
📄 `LaCC_Project.ipynb`

---

## 📂 Contents

- ✅ Experiment 1: Word-level decoding (Word2Vec vs. GloVe)
- ✅ Experiment 2–3: Sentence decoding (GloVe vs. BERT vs. BERT-PCA)
- ✅ Brain encoding analysis (voxel-level $R^2$)
- ✅ Inter-subject decoding (transfer, averaging, full-data)
- 📊 Visualizations and metrics (rank accuracy, heatmaps, $R^2$ distributions)

---

## 🚀 Running the Notebook

1. Clone the repository:

```bash
git clone https://github.com/your-username/LaCC_Project.git
cd LaCC_Project
