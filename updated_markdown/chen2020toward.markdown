---
layout: publication
title: 'Toward Subgraph-guided Knowledge Graph Question Generation With Graph Neural Networks'
authors: Yu Chen, Lingfei Wu, Mohammed J. Zaki
conference: "Arxiv"
year: 2020
citations: 33
bibkey: chen2020toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2004.06015'}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Knowledge graph (KG) question generation (QG) aims to generate natural
language questions from KGs and target answers. Previous works mostly focus on
a simple setting which is to generate questions from a single KG triple. In
this work, we focus on a more realistic setting where we aim to generate
questions from a KG subgraph and target answers. In addition, most of previous
works built on either RNN-based or Transformer based models to encode a
linearized KG sugraph, which totally discards the explicit structure
information of a KG subgraph. To address this issue, we propose to apply a
bidirectional Graph2Seq model to encode the KG subgraph. Furthermore, we
enhance our RNN decoder with node-level copying mechanism to allow directly
copying node attributes from the KG subgraph to the output question. Both
automatic and human evaluation results demonstrate that our model achieves new
state-of-the-art scores, outperforming existing methods by a significant margin
on two QG benchmarks. Experimental results also show that our QG model can
consistently benefit the Question Answering (QA) task as a mean of data
augmentation.
