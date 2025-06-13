---
layout: publication
title: 'Learning Comment Generation By Leveraging User-generated Data'
authors: Zhaojiang Lin, Genta Indra Winata, Pascale Fung
conference: "Arxiv"
year: 2018
bibkey: lin2018learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1810.12264"}
tags: ['Security', 'Model Architecture', 'RAG', 'Applications', 'Attention Mechanism']
---
Existing models on open-domain comment generation are difficult to train, and
they produce repetitive and uninteresting responses. The problem is due to
multiple and contradictory responses from a single article, and by the rigidity
of retrieval methods. To solve this problem, we propose a combined approach to
retrieval and generation methods. We propose an attentive scorer to retrieve
informative and relevant comments by leveraging user-generated data. Then, we
use such comments, together with the article, as input for a
sequence-to-sequence model with copy mechanism. We show the robustness of our
model and how it can alleviate the aforementioned issue by using a large scale
comment generation dataset. The result shows that the proposed generative model
significantly outperforms strong baseline such as Seq2Seq with attention and
Information Retrieval models by around 27 and 30 BLEU-1 points respectively.
