---
layout: publication
title: Tree Transformer Integrating Tree Structures Into Self45;attention
authors: Wang Yau-shian, Lee Hung-yi, Chen Yun-nung
conference: "Arxiv"
year: 2019
bibkey: wang2019tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.06639"}
tags: ['Attention Mechanism', 'BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Pre45;training Transformer from large45;scale raw texts and fine45;tuning on the desired task have achieved state45;of45;the45;art results on diverse NLP tasks. However it is unclear what the learned attention captures. The attention computed by attention heads seems not to match human intuitions about hierarchical structures. This paper proposes Tree Transformer which adds an extra constraint to attention heads of the bidirectional Transformer encoder in order to encourage the attention heads to follow tree structures. The tree structures can be automatically induced from raw texts by our proposed Constituent Attention module which is simply implemented by self45;attention between two adjacent words. With the same training procedure identical to BERT the experiments demonstrate the effectiveness of Tree Transformer in terms of inducing tree structures better language modeling and further learning more explainable attention scores.
