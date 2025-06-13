---
layout: publication
title: 'Citrus: Chunked Instruction-aware State Eviction For Long Sequence Modeling'
authors: Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung
conference: "Arxiv"
year: 2024
bibkey: bai2024chunked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12018"}
  - {name: "Code", url: "https://github.com/ybai-nlp/CItruS"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Long sequence modeling has gained broad interest as large language models
(LLMs) continue to advance. Recent research has identified that a large portion
of hidden states within the key-value caches of Transformer models can be
discarded (also termed evicted) without affecting the perplexity performance in
generating long sequences. However, we show that these methods, despite
preserving perplexity performance, often drop information that is important for
solving downstream tasks, a problem which we call information neglect. To
address this issue, we introduce Chunked Instruction-aware State Eviction
(CItruS), a novel modeling technique that integrates the attention preferences
useful for a downstream task into the eviction process of hidden states. In
addition, we design a method for chunked sequence processing to further improve
efficiency. Our training-free method exhibits superior performance on long
sequence comprehension and retrieval tasks over several strong baselines under
the same memory budget, while preserving language modeling perplexity. The code
and data have been released at https://github.com/ybai-nlp/CItruS.
