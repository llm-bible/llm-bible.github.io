---
layout: publication
title: LAIT Efficient Multi-segment Encoding In Transformers With Layer-adjustable Interaction
authors: Milbauer Jeremiah, Louis Annie, Hosseini Mohammad Javad, Fabrikant Alex, Metzler Donald, Schuster Tal
conference: "Arxiv"
year: 2023
bibkey: milbauer2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19585"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Transformer encoders contextualize token representations by attending to all other tokens at each layer leading to quadratic increase in compute effort with the input length. In practice however the input text of many NLP tasks can be seen as a sequence of related segments (e.g. the sequence of sentences within a passage or the hypothesis and premise in NLI). While attending across these segments is highly beneficial for many tasks we hypothesize that this interaction can be delayed until later encoding stages. To this end we introduce Layer-Adjustable Interactions in Transformers (LAIT). Within LAIT segmented inputs are first encoded independently and then jointly. This partial two-tower architecture bridges the gap between a Dual Encoders ability to pre-compute representations for segments and a fully self-attentive Transformers capacity to model cross-segment attention. The LAIT framework effectively leverages existing pretrained Transformers and converts them into the hybrid of the two aforementioned architectures allowing for easy and intuitive control over the performance-efficiency tradeoff. Experimenting on a wide range of NLP tasks we find LAIT able to reduce 30-5037; of the attention FLOPs on many tasks while preserving high accuracy; in some practical settings LAIT could reduce actual latency by orders of magnitude.
