---
layout: publication
title: TRAMS Training-free Memory Selection for Long-range Language Modeling
authors: Yu Haofei, Wang Cunxiang, Zhang Yue, Bi Wei
conference: "Arxiv"
year: 2023
bibkey: yu2023trams
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15494"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The Transformer architecture is crucial for numerous AI models but it still faces challenges in long-range language modeling. Though several specific transformer architectures have been designed to tackle issues of long-range dependencies existing methods like Transformer-XL are plagued by a high percentage of ineffective memories. In this study we present a plug-and-play strategy known as TRAining-free Memory Selection (TRAMS) that selects tokens participating in attention calculation based on one simple metric. This strategy allows us to keep tokens that are likely to have a high attention score with the current queries and ignore the other ones. We have tested our approach on the word-level benchmark (WikiText-103) and the character-level benchmark (enwik8) and the results indicate an improvement without having additional training or adding additional parameters.
