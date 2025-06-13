---
layout: publication
title: 'Xkv: Cross-layer SVD For Kv-cache Compression'
authors: Chi-chih Chang, Chien-yu Lin, Yash Akhauri, Wei-cheng Lin, Kai-chiang Wu, Luis Ceze, Mohamed S. Abdelfattah
conference: "Arxiv"
year: 2025
bibkey: chang2025cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.18893'}
  - {name: "Code", url: 'https://github.com/abdelfattah-lab/xKV'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Applications', 'Model Architecture', 'Merging', 'Pretraining Methods']
---
Large Language Models (LLMs) with long context windows enable powerful
applications but come at the cost of high memory consumption to store the Key
and Value states (KV-Cache). Recent studies attempted to merge KV-cache from
multiple layers into shared representations, yet these approaches either
require expensive pretraining or rely on assumptions of high per-token cosine
similarity across layers which generally does not hold in practice. We find
that the dominant singular vectors are remarkably well-aligned across multiple
layers of the KV-Cache. Exploiting this insight, we propose xKV, a simple
post-training method that applies Singular Value Decomposition (SVD) on the
KV-Cache of grouped layers. xKV consolidates the KV-Cache of multiple layers
into a shared low-rank subspace, significantly reducing KV-Cache sizes. Through
extensive evaluations on the RULER long-context benchmark with widely-used LLMs
(e.g., Llama-3.1 and Qwen2.5), xKV achieves up to 6.8x higher compression rates
than state-of-the-art inter-layer technique while improving accuracy by 2.7%.
Moreover, xKV is compatible with the emerging Multi-Head Latent Attention (MLA)
(e.g., DeepSeek-Coder-V2), yielding a notable 3x compression rates on coding
tasks without performance degradation. These results highlight xKV's strong
capability and versatility in addressing memory bottlenecks for long-context
LLM inference. Our code is publicly available at:
https://github.com/abdelfattah-lab/xKV.
