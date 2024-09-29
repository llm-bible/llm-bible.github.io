---
layout: publication
title: Tram A Token-level Retrieval-augmented Mechanism for Source Code Summarization
authors: Ye Tong, Wu Lingfei, Ma Tengfei, Zhang Xuhong, Du Yangkai, Liu Peiyu, Ji Shouling, Wang Wenhai
conference: "Arxiv"
year: 2023
bibkey: ye2023tram
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11074"}
tags: ['Applications', 'Merging', 'RAG']
---
Automatically generating human-readable text describing the functionality of a program is the intent of source code summarization. Although neural language models achieve significant performance in this field they are limited by their inability to access external knowledge. To address this limitation an emerging trend is combining neural models with external knowledge through retrieval methods. Previous methods have relied on the sentence-level retrieval paradigm on the encoder side. However this paradigm is coarse-grained noise-filled and cannot directly take advantage of the high-quality retrieved summary tokens on the decoder side. In this paper we propose a fine-grained Token-level retrieval-augmented mechanism (Tram) on the decoder side rather than the encoder side to enhance the performance of neural models and produce more low-frequency tokens in generating summaries. Furthermore to overcome the challenge of token-level retrieval in capturing contextual code semantics we also propose integrating code semantics into individual summary tokens. The results of extensive experiments and human evaluation show that our token-level retrieval-augmented approach significantly improves performance and is more interpretable.
