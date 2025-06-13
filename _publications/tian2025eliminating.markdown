---
layout: publication
title: 'Keepkv: Eliminating Output Perturbation In KV Cache Compression For Efficient Llms Inference'
authors: Yuxuan Tian, Zihan Wang, Yebo Peng, Aomufei Yuan, Zhiming Wang, Bairen Yi, Xin Liu, Yong Cui, Tong Yang
conference: "Arxiv"
year: 2025
bibkey: tian2025eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09936"}
tags: ['RAG', 'Model Architecture', 'Merging', 'Attention Mechanism']
---
Efficient inference of large language models (LLMs) is hindered by an
ever-growing key-value (KV) cache, making KV cache compression a critical
research direction. Traditional methods selectively evict less important KV
cache entries based on attention scores or position heuristics, which leads to
information loss and hallucinations. Recently, merging-based strategies have
been explored to retain more information by merging KV pairs that would be
discarded; however, these existing approaches inevitably introduce
inconsistencies in attention distributions before and after merging, causing
output perturbation and degraded generation quality. To overcome this
challenge, we propose KeepKV, a novel adaptive KV cache merging method designed
to eliminate output perturbation while preserving performance under strict
memory constraints. KeepKV introduces the Electoral Votes mechanism that
records merging history and adaptively adjusts attention scores. Moreover, it
further leverages a novel Zero Inference-Perturbation Merging methods, keeping
attention consistency and compensating for attention loss resulting from cache
merging. KeepKV successfully retains essential context information within a
significantly compressed cache. Extensive experiments on various benchmarks and
LLM architectures demonstrate that KeepKV substantially reduces memory usage,
enhances inference throughput by more than 2x and keeps superior generation
quality even with 10% KV cache budgets.
