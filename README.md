# 🧬 Knowledge Graph Exploration for Biological Relationships

> **M.Tech Individual Project**  
> **Timeline**: Jan 2025 – Ongoing  
> **Type**: Individual Project  
> **Guide**: [Jaspreet Kaur Dhanjal]  

---

## 📘 Overview

This project focuses on exploring biological relationships using **Knowledge Graph Embeddings** (KGE). Leveraging advanced models and message-passing architectures, we aim to understand complex interactions in biological data such as protein-protein interactions, molecular interactions, and gene-disease relationships.

---

## 🧪 Objectives

- Build and analyze **Knowledge Graphs** for biological domains.
- Utilize different embedding techniques including:
  - **BioCurie Embedding Representations**
  - **Message Passing Representations**
- Explore and compare KGE models like:
  - `ComplEx`
  - `PairRE`
  - `TransE`
  - `CompGCN`  
- Deploy experiments at scale using **Kubernetes-based distributed training**.

---

## 🧰 Tech Stack

| Tool/Library      | Purpose                            |
|------------------|------------------------------------|
| **Python**        | Core programming language          |
| **NumPy / Pandas**| Data preprocessing & manipulation  |
| **Scikit-learn**  | Evaluation metrics and analysis    |
| **Matplotlib / Seaborn** | Visualization              |
| **Kubernetes**     |For Server to run these model |
| **TensorFlow / PyTorch / PyKEEN** | Neural KGE training |
| **Kubernetes**    | Distributed model training         |

---

## 🔍 Methodology

1. **Data Acquisition**: Curated biological datasets representing entities and relationships.
2. **Graph Construction**: Formed multi-relational graphs using BioCurie formats.
3. **Embedding Techniques**:
   - Traditional: TransE, ComplEx,PairRe,AutoSF,
   - Neural: CompGCN, PairRE
   - Message Passing: GNN-style embeddings
4. **Model Training**: Scaled training using Kubernetes pods and GPU resources.
5. **Evaluation**: Performed link prediction and triple classification tasks.

---

## 🚀 Features

- Modular training and evaluation pipeline
- Easy model swapping using PyKEEN
- Streamlit interface for real-time embedding exploration
- Kubernetes cluster support for large-scale experiments

---

## 📊 Results [To be Updated]

| Model     | MRR  | Hits@1 | Hits@3 | Hits@10 |
|-----------|------|--------|--------|---------|
| TransE    | TBD  | TBD    | TBD    | TBD     |
| CompGCN   | TBD  | TBD    | TBD    | TBD     |
| PairRE    | TBD  | TBD    | TBD    | TBD     |

---

## 🏁 Future Work

- Integrate **transformer-based KGE models**
- Fine-tune embeddings on specific biomedical tasks
- Deploy public demo of interactive graph exploration

---


