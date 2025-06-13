---
layout: publication
title: 'Duodecoding: Hardware-aware Heterogeneous Speculative Decoding With Dynamic Multi-sequence Drafting'
authors: Kai Lv, Honglin Guo, Qipeng Guo, Xipeng Qiu
conference: "Arxiv"
year: 2025
bibkey: lv2025hardware
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00784"}
  - {name: "Code", url: "https://github.com/KaiLv69/DuoDecoding"}
tags: ['Tools', 'GPT', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) exhibit exceptional performance across a wide
range of tasks; however, their token-by-token autoregressive generation process
significantly hinders inference speed. Speculative decoding presents a
promising draft-then-verify framework that reduces generation latency while
maintaining output distribution fidelity. Nevertheless, the draft model
introduces additional computational overhead, becoming a performance bottleneck
and increasing the time to first token (TTFT). Previous approaches to mitigate
draft model overhead have primarily relied on heuristics and generally failed
to match the quality of the draft language models. To address these challenges,
we propose DuoDecoding, a novel approach that strategically deploys the draft
and target models on the CPU and GPU respectively, enabling parallel decoding
while preserving draft quality. Our method incorporates a hardware-aware
optimal draft budget to minimize idle times and employs dynamic multi-sequence
drafting to enhance draft quality. Extensive experiments across seven tasks
show that DuoDecoding achieves up to 2.61x speedup in generation latency, while
reducing TTFT to 83% of that in conventional speculative decoding. The Code is
available at https://github.com/KaiLv69/DuoDecoding.
