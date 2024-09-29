---
layout: publication
title: 'Stronger Transformers For Neural Multi-hop Question Generation'
authors: Sachan Devendra Singh, Wu Lingfei, Sachan Mrinmaya, Hamilton William
conference: "Arxiv"
year: 2020
bibkey: sachan2020stronger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.11374"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Prior work on automated question generation has almost exclusively focused on generating simple questions whose answers can be extracted from a single document. However there is an increasing interest in developing systems that are capable of more complex multi-hop question generation where answering the questions requires reasoning over multiple documents. In this work we introduce a series of strong transformer models for multi-hop question generation including a graph-augmented transformer that leverages relations between entities in the text. While prior work has emphasized the importance of graph-based models we show that we can substantially outperform the state-of-the-art by 5 BLEU points using a standard transformer architecture. We further demonstrate that graph-based augmentations can provide complimentary improvements on top of this foundation. Interestingly we find that several important factors--such as the inclusion of an auxiliary contrastive objective and data filtering could have larger impacts on performance. We hope that our stronger baselines and analysis provide a constructive foundation for future work in this area.
