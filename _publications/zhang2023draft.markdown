---
layout: publication
title: Draft & Verify: Lossless Large Language Model Acceleration Via Self-speculative Decoding
authors: Zhang Jun, Wang Jue, Li Huan, Shou Lidan, Chen Ke, Chen Gang, Mehrotra Sharad
conference: "Arxiv"
year: 2023
bibkey: zhang2023draft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08168"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
We present a novel inference scheme self-speculative decoding for accelerating Large Language Models (LLMs) without the need for an auxiliary model. This approach is characterized by a two-stage process drafting and verification. The drafting stage generates draft tokens at a slightly lower quality but more quickly which is achieved by selectively skipping certain intermediate layers during drafting. Subsequently the verification stage employs the original LLM to validate those draft output tokens in one forward pass. This process ensures the final output remains identical to that produced by the unaltered LLM. Moreover the proposed method requires no additional neural network training and no extra memory footprint making it a plug-and-play and cost-effective solution for inference acceleration. Benchmarks with LLaMA-2 and its variants demonstrated a speedup up to 1.99(times).
