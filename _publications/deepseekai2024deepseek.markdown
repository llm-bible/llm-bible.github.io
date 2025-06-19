---
layout: publication
title: Deepseek-v3 Technical Report
authors: Deepseek-ai et al.
conference: Arxiv
year: 2024
citations: 25
bibkey: deepseekai2024deepseek
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.19437'}, {name: Code,
    url: 'https://github.com/deepseek-ai/DeepSeek-V3'}]
tags: [Fine-Tuning, Reinforcement Learning, Agentic, Model Architecture, Attention
    Mechanism]
---
We present DeepSeek-V3, a strong Mixture-of-Experts (MoE) language model with
671B total parameters with 37B activated for each token. To achieve efficient
inference and cost-effective training, DeepSeek-V3 adopts Multi-head Latent
Attention (MLA) and DeepSeekMoE architectures, which were thoroughly validated
in DeepSeek-V2. Furthermore, DeepSeek-V3 pioneers an auxiliary-loss-free
strategy for load balancing and sets a multi-token prediction training
objective for stronger performance. We pre-train DeepSeek-V3 on 14.8 trillion
diverse and high-quality tokens, followed by Supervised Fine-Tuning and
Reinforcement Learning stages to fully harness its capabilities. Comprehensive
evaluations reveal that DeepSeek-V3 outperforms other open-source models and
achieves performance comparable to leading closed-source models. Despite its
excellent performance, DeepSeek-V3 requires only 2.788M H800 GPU hours for its
full training. In addition, its training process is remarkably stable.
Throughout the entire training process, we did not experience any irrecoverable
loss spikes or perform any rollbacks. The model checkpoints are available at
https://github.com/deepseek-ai/DeepSeek-V3.