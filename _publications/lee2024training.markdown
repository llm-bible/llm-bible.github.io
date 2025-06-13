---
layout: publication
title: 'A Training-free Sub-quadratic Cost Transformer Model Serving Framework With Hierarchically Pruned Attention'
authors: Heejun Lee, Geon Park, Youngwan Lee, Jaduk Suh, Jina Kim, Wonyoung Jeong, Bumsik Kim, Hyemin Lee, Myeongjae Jeon, Sung Ju Hwang
conference: "Arxiv"
year: 2024
bibkey: lee2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09827"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
In modern large language models (LLMs), increasing the context length is
crucial for improving comprehension and coherence in long-context, multi-modal,
and retrieval-augmented language generation. While many recent transformer
models attempt to extend their context length over a million tokens, they
remain impractical due to the quadratic time and space complexities. Although
recent works on linear and sparse attention mechanisms can achieve this goal,
their real-world applicability is often limited by the need to re-train from
scratch and significantly worse performance. In response, we propose a novel
approach, Hierarchically Pruned Attention (HiP), which reduces the time
complexity of the attention mechanism to \\(O(T log T)\\) and the space complexity
to \\(O(T)\\), where \\(T\\) is the sequence length. We notice a pattern in the
attention scores of pretrained LLMs where tokens close together tend to have
similar scores, which we call ``attention locality''. Based on this
observation, we utilize a novel tree-search-like algorithm that estimates the
top-\\(k\\) key tokens for a given query on the fly, which is mathematically
guaranteed to have better performance than random attention pruning. In
addition to improving the time complexity of the attention mechanism, we
further optimize GPU memory usage by implementing KV cache offloading, which
stores only \\(O(log T)\\) tokens on the GPU while maintaining similar decoding
throughput. Experiments on benchmarks show that HiP, with its training-free
nature, significantly reduces both prefill and decoding latencies, as well as
memory usage, while maintaining high-quality generation with minimal
degradation. HiP enables pretrained LLMs to scale up to millions of tokens on
commodity GPUs, potentially unlocking long-context LLM applications previously
deemed infeasible.
