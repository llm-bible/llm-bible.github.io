---
layout: publication
title: 'Multiplicative Position-aware Transformer Models For Language Understanding'
authors: Zhiheng Huang, Davis Liang, Peng Xu, Bing Xiang
conference: "Arxiv"
year: 2021
bibkey: huang2021multiplicative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.12788"}
tags: ['Model Architecture', 'Survey Paper', 'RAG', 'Pretraining Methods', 'BERT', 'Transformer', 'Attention Mechanism']
---
Transformer models, which leverage architectural improvements like
self-attention, perform remarkably well on Natural Language Processing (NLP)
tasks. The self-attention mechanism is position agnostic. In order to capture
positional ordering information, various flavors of absolute and relative
position embeddings have been proposed. However, there is no systematic
analysis on their contributions and a comprehensive comparison of these methods
is missing in the literature. In this paper, we review major existing position
embedding methods and compare their accuracy on downstream NLP tasks, using our
own implementations. We also propose a novel multiplicative embedding method
which leads to superior accuracy when compared to existing methods. Finally, we
show that our proposed embedding method, served as a drop-in replacement of the
default absolute position embedding, can improve the RoBERTa-base and
RoBERTa-large models on SQuAD1.1 and SQuAD2.0 datasets.
