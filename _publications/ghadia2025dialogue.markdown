---
layout: publication
title: 'Dialogue Without Limits: Constant-sized KV Caches For Extended Responses In Llms'
authors: Ravi Ghadia, Avinash Kumar, Gaurav Jain, Prashant Nair, Poulami Das
conference: "Arxiv"
year: 2025
bibkey: ghadia2025dialogue
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00979'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Autoregressive Transformers rely on Key-Value (KV) caching to accelerate
inference. However, the linear growth of the KV cache with context length leads
to excessive memory consumption and bandwidth constraints. This bottleneck is
particularly problematic in real-time applications -- such as chatbots and
interactive assistants -- where low latency and high memory efficiency are
critical. Existing methods drop distant tokens or compress states in a lossy
manner, sacrificing accuracy by discarding vital context or introducing bias.
  We propose MorphKV, an inference-time technique that maintains a
constant-sized KV cache while preserving accuracy. MorphKV balances long-range
dependencies and local coherence during text generation. It eliminates
early-token bias while retaining high-fidelity context by adaptively ranking
tokens through correlation-aware selection. Unlike heuristic retention or lossy
compression, MorphKV iteratively refines the KV cache via lightweight updates
guided by attention patterns of recent tokens. This approach captures
inter-token correlation with greater accuracy, crucial for tasks like content
creation and code generation. Our studies on long-response tasks show 52.9\\(%\\)
memory savings and 18.2\\(%\\) higher accuracy on average compared to
state-of-the-art prior works, enabling efficient real-world deployment.
