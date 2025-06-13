---
layout: publication
title: 'Autobert-zero: Evolving BERT Backbone From Scratch'
authors: Jiahui Gao, Hang Xu, Han Shi, Xiaozhe Ren, Philip L. H. Yu, Xiaodan Liang, Xin Jiang, Zhenguo Li
conference: "Arxiv"
year: 2021
bibkey: gao2021autobert
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2107.07445'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'BERT', 'Fine-Tuning', 'Ethics and Bias', 'Pretraining Methods']
---
Transformer-based pre-trained language models like BERT and its variants have
recently achieved promising performance in various natural language processing
(NLP) tasks. However, the conventional paradigm constructs the backbone by
purely stacking the manually designed global self-attention layers, introducing
inductive bias and thus leads to sub-optimal. In this work, we make the first
attempt to automatically discover novel pre-trained language model (PLM)
backbone on a flexible search space containing the most fundamental operations
from scratch. Specifically, we propose a well-designed search space which (i)
contains primitive math operations in the intra-layer level to explore novel
attention structures, and (ii) leverages convolution blocks to be the
supplementary for attentions in the inter-layer level to better learn local
dependency. To enhance the efficiency for finding promising architectures, we
propose an Operation-Priority Neural Architecture Search (OP-NAS) algorithm,
which optimizes both the search algorithm and evaluation of candidate models.
Specifically, we propose Operation-Priority (OP) evolution strategy to
facilitate model search via balancing exploration and exploitation.
Furthermore, we design a Bi-branch Weight-Sharing (BIWS) training strategy for
fast model evaluation. Extensive experiments show that the searched
architecture (named AutoBERT-Zero) significantly outperforms BERT and its
variants of different model capacities in various downstream tasks, proving the
architecture's transfer and scaling abilities. Remarkably, AutoBERT-Zero-base
outperforms RoBERTa-base (using much more data) and BERT-large (with much
larger model size) by 2.4 and 1.4 higher score on GLUE test set.
