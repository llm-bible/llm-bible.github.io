---
layout: publication
title: 'Glinthawk: A Two-tiered Architecture For Offline LLM Inference'
authors: Pouya Hamadanian, Sadjad Fouladi
conference: "Arxiv"
year: 2025
bibkey: hamadanian2025two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11779"}
  - {name: "Code", url: "https://github.com/microsoft/glinthawk"}
tags: ['Applications', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Has Code']
---
We introduce Glinthawk, an architecture for offline Large Language Model
(LLM) inference. By leveraging a two-tiered structure, Glinthawk optimizes the
utilization of the high-end accelerators ("Tier 1") by offloading the attention
mechanism to lower-end compute tier ("Tier 2"). This separation allows the
memory demand of the attention, known as the key-value cache, to scale
independently from the model weights, enabling larger batch sizes and more
efficient accelerator usage. Prototyped with NVIDIA T4 GPUs and standard CPU
VMs, Glinthawk improves throughput by \\(5.9\times\\) and reduces cost of
generation by \\(2.8\times\\), compared to paged attention baselines. For long
sequence lengths, it achieves \\(16.3\times\\) throughput improvement at
\\(2.4\times\\) less cost. Our evaluation shows that this architecture can tolerate
moderate network latency with minimal performance degradation, making it highly
effective for latency-tolerant, throughput-focused applications such as batch
processing. The prototype is publicly available at
https://github.com/microsoft/glinthawk.
