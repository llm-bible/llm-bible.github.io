---
layout: publication
title: 'Mind The Gap: A Generalized Approach For Cross-modal Embedding Alignment'
authors: Arihan Yadav, Alan Mcmillan
conference: "Arxiv"
year: 2024
bibkey: yadav2024mind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23437"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Language Modeling', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Retrieval-Augmented Generation (RAG) systems enhance text generation by
incorporating external knowledge but often struggle when retrieving context
across different text modalities due to semantic gaps. We introduce a
generalized projection-based method, inspired by adapter modules in transfer
learning, that efficiently bridges these gaps between various text types, such
as programming code and pseudocode, or English and French sentences. Our
approach emphasizes speed, accuracy, and data efficiency, requiring minimal
resources for training and inference. By aligning embeddings from heterogeneous
text modalities into a unified space through a lightweight projection network,
our model significantly outperforms traditional retrieval methods like the
Okapi BM25 algorithm and models like Dense Passage Retrieval (DPR), while
approaching the accuracy of Sentence Transformers. Extensive evaluations
demonstrate the effectiveness and generalizability of our method across
different tasks, highlighting its potential for real-time, resource-constrained
applications.
