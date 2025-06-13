---
layout: publication
title: 'M2R2: Mixture Of Multi-rate Residuals For Efficient Transformer Inference'
authors: Nikhil Bhendawade, Mahyar Najibi, Devang Naik, Irina Belousova
conference: "Arxiv"
year: 2025
bibkey: bhendawade2025mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02040'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Residual transformations enhance the representational depth and expressive
power of large language models (LLMs). However, applying static residual
transformations across all tokens in auto-regressive generation leads to a
suboptimal trade-off between inference efficiency and generation fidelity.
Existing methods, including Early Exiting, Skip Decoding, and Mixture-of-Depth
address this by modulating the residual transformation based on token-level
complexity. Nevertheless, these approaches predominantly consider the distance
traversed by tokens through the model layers, neglecting the underlying
velocity of residual evolution. We introduce Mixture of Multi-rate Residuals
(M2R2), a framework that dynamically modulates residual velocity to improve
early alignment, enhancing inference efficiency. Evaluations on reasoning
oriented tasks such as Koala, Self-Instruct, WizardLM, and MT-Bench show M2R2
surpasses state-of-the-art distance-based strategies, balancing generation
quality and speedup. In self-speculative decoding setup, M2R2 achieves up to
2.8x speedups on MT-Bench, outperforming methods like 2-model speculative
decoding, Medusa, LookAhead Decoding, and DEED. In Mixture-of-Experts (MoE)
architectures, integrating early residual alignment with ahead-of-time expert
loading into high-bandwidth memory (HBM) accelerates decoding, reduces
expert-switching bottlenecks, and achieves a 2.9x speedup, making it highly
effective in resource-constrained environments.
