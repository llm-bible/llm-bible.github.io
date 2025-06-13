---
layout: publication
title: 'MOM: Memory-efficient Offloaded Mini-sequence Inference For Long Context Language Models'
authors: Junyang Zhang, Tianyi Zhu, Cheng Luo, Anima Anandkumar
conference: "Arxiv"
year: 2025
bibkey: zhang2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12526"}
tags: ['RAG', 'Efficiency and Optimization']
---
Long-context language models exhibit impressive performance but remain
challenging to deploy due to high GPU memory demands during inference. We
propose Memory-efficient Offloaded Mini-sequence Inference (MOM), a method that
partitions critical layers into smaller "mini-sequences" and integrates
seamlessly with KV cache offloading. Experiments on various Llama, Qwen, and
Mistral models demonstrate that MOM reduces peak memory usage by over 50% on
average. On Meta-Llama-3.2-8B, MOM extends the maximum context length from 155k
to 455k tokens on a single A100 80GB GPU, while keeping outputs identical and
not compromising accuracy. MOM also maintains highly competitive throughput due
to minimal computational overhead and efficient last-layer processing. Compared
to traditional chunked prefill methods, MOM achieves a 35% greater context
length extension. More importantly, our method drastically reduces prefill
memory consumption, eliminating it as the longstanding dominant memory
bottleneck during inference. This breakthrough fundamentally changes research
priorities, redirecting future efforts from prefill-stage optimizations to
improving decode-stage residual KV cache efficiency.
