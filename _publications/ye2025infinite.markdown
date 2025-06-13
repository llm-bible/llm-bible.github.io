---
layout: publication
title: 'Infinite Retrieval: Attention Enhanced Llms In Long-context Processing'
authors: Xiaoju Ye, Zhichun Wang, Jingyuan Wang
conference: "Arxiv"
year: 2025
bibkey: ye2025infinite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12962"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Limited by the context window size of Large Language Models(LLMs), handling
various tasks with input tokens exceeding the upper limit has been challenging,
whether it is a simple direct retrieval task or a complex multi-hop reasoning
task. Although various methods have been proposed to enhance the long-context
processing capabilities of LLMs, they either incur substantial post-training
costs, or require additional tool modules(e.g.,RAG), or have not shown
significant improvement in realistic tasks. Our work observes the correlation
between the attention distribution and generated answers across each layer, and
establishes the attention allocation aligns with retrieval-augmented
capabilities through experiments. Drawing on the above insights, we propose a
novel method InfiniRetri that leverages the LLMs's own attention information to
enable accurate retrieval across inputs of infinitely length. Our evaluations
indicate that InfiniRetri achieves 100% accuracy in the
Needle-In-a-Haystack(NIH) test over 1M tokens using a 0.5B parameter model,
surpassing other method or larger models and setting a new
state-of-the-art(SOTA). Moreover, our method achieves significant performance
improvements on real-world benchmarks, with a maximum 288% improvement. In
addition, InfiniRetri can be applied to any Transformer-based LLMs without
additional training and substantially reduces inference latency and compute
overhead in long texts. In summary, our comprehensive studies show
InfiniRetri's potential for practical applications and creates a paradigm for
retrievaling information using LLMs own capabilities under infinite-length
tokens. Code will be released in link.
