---
layout: publication
title: 'Windowkv: Task-adaptive Group-wise KV Cache Window Selection For Efficient LLM Inference'
authors: Youhui Zuo, Sibo Wei, Chen Zhang, Zhuorui Liu, Wenpeng Lu, Dawei Song
conference: "Arxiv"
year: 2025
bibkey: zuo2025task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17922"}
tags: ['Security', 'Efficiency and Optimization', 'Reinforcement Learning']
---
With the advancements in long-context inference capabilities of large
language models (LLMs), the KV cache has become one of the foundational
components. However, its substantial GPU memory consumption makes KV cache
compression a key technique for enabling efficient LLM inference in industrial
scenarios. While recent studies have focused on optimizing the memory occupied
by the KV cache, they overlook two critical factors: preserving semantic
coherence and considering task-specific characteristic during compression. To
address these limitations, we propose a novel task-adaptive KV cache window
selection method, WindowKV. WindowKV dynamically selects local semantic windows
consisting of consecutive tokens, according to task-specific characteristics,
ensuring the retained KV cache captures continuous, essential context.
Additionally, we introduce an intra-group layer KV cache indices sharing
strategy to reduce computational overhead, achieving a balance between
performance and efficiency. We rigorously evaluate WindowKV on the LongBench
benchmark, and the results demonstrate that it maintains a performance
comparable to full KV cache retention while using only 12% of the original KV
cache, significantly reducing memory requirements. Furthermore, our method also
achieves state-of-the-art results in the Needle-in-a-Haystack evaluation,
highlighting its effectiveness and robustness.
