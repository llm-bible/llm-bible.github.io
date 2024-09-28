---
layout: publication
title: T-FREE Tokenizer-Free Generative LLMs via Sparse Representations for Memory-Efficient Embeddings
authors: Deiseroth Björn, Brack Manuel, Schramowski Patrick, Kersting Kristian, Weinbach Samuel
conference: "Arxiv"
year: 2024
bibkey: deiseroth2024t
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19223"}
tags: ['ARXIV', 'Ethics And Bias', 'Fine Tuning', 'LLM']
---
Tokenizers are crucial for encoding information in Large Language Models but their development has recently stagnated and they contain inherent weaknesses. Major limitations include computational overhead ineffective vocabulary use and unnecessarily large embedding and head layers. Additionally their performance is biased towards a reference corpus leading to reduced effectiveness for underrepresented languages. To remedy these issues we propose T-FREE which directly embeds words through sparse activation patterns over character triplets and does not require a reference corpus. T-FREE inherently exploits morphological similarities and allows for strong compression of embedding layers. In our exhaustive experimental evaluation we achieve competitive downstream performance with a parameter reduction of more than 85 on these layers. Further T-FREE shows significant improvements in cross-lingual transfer learning.
