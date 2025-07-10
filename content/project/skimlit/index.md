---
title: SkimLit – Biomedical Abstract Sentence Classifier
date: 2025-07-10
external_link: https://www.kaggle.com/code/josephengineer112/pub-med-rct-summary
tags:
  - NLP
  - Biomedical AI
  - BERT
  - Sentence Classification
  - Deep Learning
---

SkimLit is an advanced NLP-based project designed to classify sentences in biomedical abstracts into rhetorical categories like **Objective**, **Methods**, **Results**, **Background**, and **Conclusion**. It helps researchers quickly skim through large volumes of biomedical literature by automatically organizing abstract content.

<!--more-->

**Key Features:**
- 📚 Trained on the **PubMed 20k RCT dataset** for real-world biomedical sentence classification.
- 🧠 Uses a **multi-input neural architecture** combining:
  - **BERT-based token embeddings**
  - **Character-level BiLSTM representations**
  - **Sentence positional features** (line number, total lines)
- 🔁 Employs **attention and gating mechanisms** for refined context-aware feature fusion.
- 📈 Achieved **90.57% accuracy**, outperforming several baseline models.
- ⚡ Built for efficiency and runs in **low-compute environments** (no fine-tuning of BERT required).

**Architecture Highlights:**
- Semantic understanding via **frozen pre-trained BERT** embeddings
- Character-level context via **Bidirectional LSTM**
- Structural awareness via **sentence position encodings**
- Intelligent **attention mechanism** to weigh feature importance