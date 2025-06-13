---
layout: publication
title: 'MARE: Multi-aspect Rationale Extractor On Unsupervised Rationale Extraction'
authors: Han Jiang, Junwen Duan, Zhe Qu, Jianxin Wang
conference: "Arxiv"
year: 2024
bibkey: jiang2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03531'}
  - {name: "Code", url: 'https://github.com/CSU-NLP-Group/MARE'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning']
---
Unsupervised rationale extraction aims to extract text snippets to support
model predictions without explicit rationale annotation. Researchers have made
many efforts to solve this task. Previous works often encode each aspect
independently, which may limit their ability to capture meaningful internal
correlations between aspects. While there has been significant work on
mitigating spurious correlations, our approach focuses on leveraging the
beneficial internal correlations to improve multi-aspect rationale extraction.
In this paper, we propose a Multi-Aspect Rationale Extractor (MARE) to explain
and predict multiple aspects simultaneously. Concretely, we propose a
Multi-Aspect Multi-Head Attention (MAMHA) mechanism based on hard deletion to
encode multiple text chunks simultaneously. Furthermore, multiple special
tokens are prepended in front of the text with each corresponding to one
certain aspect. Finally, multi-task training is deployed to reduce the training
overhead. Experimental results on two unsupervised rationale extraction
benchmarks show that MARE achieves state-of-the-art performance. Ablation
studies further demonstrate the effectiveness of our method. Our codes have
been available at https://github.com/CSU-NLP-Group/MARE.
