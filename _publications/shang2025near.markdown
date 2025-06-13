---
layout: publication
title: 'Longrope2: Near-lossless LLM Context Window Scaling'
authors: Ning Shang, Li Lyna Zhang, Siyuan Wang, Gaokai Zhang, Gilsinia Lopez, Fan Yang, Weizhu Chen, Mao Yang
conference: "Arxiv"
year: 2025
bibkey: shang2025near
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20082"}
  - {name: "Code", url: "https://github.com/microsoft/LongRoPE"}
tags: ['Training Techniques', 'Has Code']
---
LongRoPE2 is a novel approach that extends the effective context window of
pre-trained large language models (LLMs) to the target length, while preserving
the performance on the original shorter context window. This is achieved by
three contributions: (1) a hypothesis that insufficient training in higher RoPE
dimensions contributes to the persistent out-of-distribution (OOD) issues
observed in existing methods; (2) an effective RoPE rescaling algorithm that
adopts evolutionary search guided by "needle-driven" perplexity to address the
insufficient training problem; (3) a mixed context window training approach
that fine-tunes model weights to adopt rescaled RoPE for long-context sequences
while preserving the short-context performance with the original RoPE.
Extensive experiments on LLaMA3-8B and Phi3-mini-3.8B across various benchmarks
validate the hypothesis and demonstrate the effectiveness of LongRoPE2.
Remarkably, LongRoPE2 extends LLaMA3-8B to achieve a 128K effective context
length while retaining over 98.5% of short-context performance, using only 10B
tokens -- 80x fewer than Meta's approach, which fails to reach the target
effective context length. Code will be available at
https://github.com/microsoft/LongRoPE.
