---
layout: publication
title: Picking The Underused Heads A Network Pruning Perspective Of Attention Head Selection For Fusing Dialogue Coreference Information
authors: Liu Zhengyuan, Chen Nancy F.
conference: "Arxiv"
year: 2023
bibkey: liu2023picking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09541"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Training Techniques', 'Transformer']
---
The Transformer45;based models with the multi45;head self45;attention mechanism are widely used in natural language processing and provide state45;of45;the45;art results. While the pre45;trained language backbones are shown to implicitly capture certain linguistic knowledge explicitly incorporating structure45;aware features can bring about further improvement on the downstream tasks. However such enhancement often requires additional neural components and increases training parameter size. In this work we investigate the attention head selection and manipulation strategy for feature injection from a network pruning perspective and conduct a case study on dialogue summarization. We first rank attention heads in a Transformer45;based summarizer with layer45;wise importance. We then select the underused heads through extensive analysis and inject structure45;aware features by manipulating the selected heads. Experimental results show that the importance45;based head selection is effective for feature injection and dialogue summarization can be improved by incorporating coreference information via head manipulation.
