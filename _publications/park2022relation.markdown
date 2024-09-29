---
layout: publication
title: "Relation-aware Language-graph Transformer For Question Answering"
authors: Park Jinyoung, Choi Hyeong Kyu, Ko Juyeon, Park Hyeonjin, Kim Ji-hoon, Jeong Jisu, Kim Kyungmin, Kim Hyunwoo J.
conference: "Arxiv"
year: 2022
bibkey: park2022relation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.00975"}
  - {name: "Code", url: "http://github.com/mlvlab/QAT"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
Question Answering (QA) is a task that entails reasoning over natural language contexts and many relevant works augment language models (LMs) with graph neural networks (GNNs) to encode the Knowledge Graph (KG) information. However most existing GNN-based modules for QA do not take advantage of rich relational information of KGs and depend on limited information interaction between the LM and the KG. To address these issues we propose Question Answering Transformer (QAT) which is designed to jointly reason over language and graphs with respect to entity relations in a unified manner. Specifically QAT constructs Meta-Path tokens which learn relation-centric embeddings based on diverse structural and semantic relations. Then our Relation-Aware Self-Attention module comprehensively integrates different modalities via the Cross-Modal Relative Position Bias which guides information exchange between relevant entites of different modalities. We validate the effectiveness of QAT on commonsense question answering datasets like CommonsenseQA and OpenBookQA and on a medical question answering dataset MedQA-USMLE. On all the datasets our method achieves state-of-the-art performance. Our code is available at http://github.com/mlvlab/QAT."
