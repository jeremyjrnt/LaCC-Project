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

## 🧠 Data Used

The project uses fMRI data from:

🧪 **Pereira et al., 2018 — Naturalistic fMRI Benchmark Dataset**

- 📁 **Experiment 1**: 180 individual concepts presented with sentence, word cloud, and image  
  - Used for word-level decoding and inter-subject generalization  
  - Files: `M##_avg.csv` (averaged voxel responses per subject)  
  - ✅ In this repository, we provide the PCA-projected versions of these vectors:  
    `M##_avg_pca.csv` for subjects 01 to 15 (each reduced to 180 dimensions using PCA)

- 📁 **Experiment 2**: 384 sentences across 96 passages (24 topics)  
  - Used for sentence-level decoding and encoding  
  - File: `EXP2.pkl` and sentence embeddings (GloVe, BERT)

- 📁 **Experiment 3**: 243 new sentences from unseen topics  
  - Used to evaluate generalization of sentence decoders

---

🔗 **Download the original dataset** from the MIT EvLab repository:  
👉 [https://web.mit.edu/evlab//sites/default/files/documents/index2.html](https://web.mit.edu/evlab//sites/default/files/documents/index2.html)


🔗 **Download the original dataset** from the MIT EvLab repository:  
👉 [https://web.mit.edu/evlab//sites/default/files/documents/index2.html](https://web.mit.edu/evlab//sites/default/files/documents/index2.html)

---

## 🚀 Running the Notebook

1. Clone the repository:

```bash
git clone https://github.com/your-username/LaCC_Project.git
cd LaCC_Project
