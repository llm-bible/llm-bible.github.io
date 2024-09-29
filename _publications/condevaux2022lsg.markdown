---
layout: publication
title: LSG Attention Extrapolation of pretrained Transformers to long sequences
authors: Condevaux Charles, Harispe Sébastien
conference: "Arxiv"
year: 2022
bibkey: condevaux2022lsg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.15497"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer models achieve state-of-the-art performance on a wide range of NLP tasks. They however suffer from a prohibitive limitation due to the self-attention mechanism inducing O(n^2) complexity with regard to sequence length. To answer this limitation we introduce the LSG architecture which relies on Local Sparse and Global attention. We show that LSG attention is fast efficient and competitive in classification and summarization tasks on long documents. Interestingly it can also be used to adapt existing pretrained models to efficiently extrapolate to longer sequences with no additional training. Along with the introduction of the LSG attention mechanism we propose tools to train new models and adapt existing ones based on this mechanism.
