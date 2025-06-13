---
layout: publication
title: 'Progressive Sparse Attention: Algorithm And System Co-design For Efficient Attention In LLM Serving'
authors: Qihui Zhou, Peiqi Yin, Pengfei Zuo, James Cheng
conference: "Arxiv"
year: 2025
bibkey: zhou2025progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00392"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
Processing long contexts has become a critical capability for modern large
language models (LLMs). However, serving long-context LLMs comes with
significant inference costs due to the high memory overhead of the key-value
(KV) cache. Existing work leverages dynamic sparse attention algorithms (DSAes)
to mitigate the KV cache overhead, but these algorithms rely on top-\\(k\\) KV
cache selection, which results in a trade-off between accuracy and efficiency.
A larger \\(k\\) improves accuracy but decreases efficiency, while a smaller \\(k\\)
boosts efficiency but compromises accuracy. To overcome this trade-off, this
paper presents PSA, a \\(\underline\{P\}\\)rogressive \\(\underline\{S\}\\)parse
\\(\underline\{A\}\\)ttention mechanism that integrates algorithmic innovations with
system co-design to achieve both high inference accuracy and improved
efficiency in LLM serving. The PSA algorithm adaptively adjusts the KV cache
budget of different tokens and layers according to their real attention weight
distributions, rather than relying on a fixed budget \\(k\\). This enables high
accuracy while minimizing KV cache usage. To further enhance execution
efficiency, we introduce a pipelined iteration scheme that reduces CPU-GPU
interleaving and synchronization overhead during PSA computation. Additionally,
we implement unified GPU memory management that optimizes PSA's memory
utilization by accounting for uneven memory requirements across different model
layers. Extensive experimental results demonstrate that PSA reduces KV cache
usage for attention computation by up to 2.4\\(\times\\) and 8.8\\(\times\\), and
increases end-to-end serving throughput by up to 1.4\\(\times\\) and 2.0\\(\times\\),
compared to state-of-the-art DSAes and systems without sparse attention,
respectively.
