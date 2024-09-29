---
layout: publication
title: "Context Compression For Auto-regressive Transformers With Sentinel Tokens"
authors: Ren Siyu, Jia Qi, Zhu Kenny Q.
conference: "Arxiv"
year: 2023
bibkey: ren2023context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08152"}
  - {name: "Code", url: "https://github.com/DRSY/KV_Compression"}
tags: ['Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The quadratic complexity of the attention module makes it gradually become the bulk of compute in Transformer-based LLMs during generation. Moreover the excessive key-value cache that arises when dealing with long inputs also brings severe issues on memory footprint and inference latency. In this work we propose a plug-and-play approach that is able to incrementally compress the intermediate activation of a specified span of tokens into compact ones thereby reducing both memory and computational cost when processing subsequent context. Experiments on both in-domain language modeling and zero-shot open-ended document generation demonstrate the advantage of our approach over sparse attention baselines in terms of fluency n-gram matching and semantic similarity. At last we comprehensively profile the benefit of context compression on improving the system throughout. Code is available at https://github.com/DRSY/KV\_Compression."
