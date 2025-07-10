---
title: 'An Optimized Framework for Contextual Sentence Classification in Biomedical Abstracts'

# Authors
authors:
  - admin
  - Muhammad Hammad

author_notes:
  - "Equal contribution"
  - "Equal contribution"

date: '2025-05-14T00:00:00Z'
publishDate: '2025-07-07T00:00:00Z'

doi: ''

publication_types: ['article-journal']

publication: In *ResearchGate*
publication_short: In *ResearchGate*

abstract: |
  We propose a novel multi-input architecture for sentence classification of biomedical abstracts. By combining BERT-based contextual embeddings, character-level BiLSTM processing, and structural features like sentence position within an abstract, our model achieves 90.57% accuracy on the PubMed 20k RCT dataset. The architecture balances performance with computational efficiency and is well-suited for low-resource environments.

summary: |
  A multi-input neural network combining BERT, BiLSTM, and sentence-level positional features for medical abstract classification.

tags:
  - BERT
  - NLP
  - Sentence Classification
  - Biomedical Informatics

featured: true

url_pdf: ''
url_code: https://www.kaggle.com/code/josephengineer112/pub-med-rct-summary-nlp-ann
url_dataset: https://github.com/Franck-Dernoncourt/pubmed-rct
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []

slides: ""
---

{{% callout note %}}
This paper presents an efficient and accurate model for classifying sentences in biomedical abstracts using a fusion of token-level, character-level, and positional features.
{{% /callout %}}

The model integrates:
- **BERT embeddings** to capture sentence-level semantics.
- **Character-level BiLSTM** layers to handle biomedical terminology and subword patterns.
- **Positional encodings** based on line number and abstract structure.

Evaluation on the PubMed 20k RCT dataset shows a classification accuracy of **90.57%**, outperforming previous architectures like Forward ANN, CRF, and logistic regression models.

This work is a step forward in making large-scale biomedical literature more searchable, structured, and interpretable.