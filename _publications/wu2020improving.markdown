---
layout: publication
title: 'Improving Attention Mechanism With Query-value Interaction'
authors: Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang
conference: "Arxiv"
year: 2020
bibkey: wu2020improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03766"}
tags: ['Transformer', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'BERT']
---
Attention mechanism has played critical roles in various state-of-the-art NLP
models such as Transformer and BERT. It can be formulated as a ternary function
that maps the input queries, keys and values into an output by using a
summation of values weighted by the attention weights derived from the
interactions between queries and keys. Similar with query-key interactions,
there is also inherent relatedness between queries and values, and
incorporating query-value interactions has the potential to enhance the output
by learning customized values according to the characteristics of queries.
However, the query-value interactions are ignored by existing attention
methods, which may be not optimal. In this paper, we propose to improve the
existing attention mechanism by incorporating query-value interactions. We
propose a query-value interaction function which can learn query-aware
attention values, and combine them with the original values and attention
weights to form the final output. Extensive experiments on four datasets for
different tasks show that our approach can consistently improve the performance
of many attention-based models by incorporating query-value interactions.
