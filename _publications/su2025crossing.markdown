---
layout: publication
title: 'Crossing The Reward Bridge: Expanding RL With Verifiable Rewards Across Diverse Domains'
authors: Yi Su, Dian Yu, Linfeng Song, Juntao Li, Haitao Mi, Zhaopeng Tu, Min Zhang, Dong Yu
conference: "Arxiv"
year: 2025
bibkey: su2025crossing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23829'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Reinforcement learning with verifiable rewards (RLVR) has demonstrated
significant success in enhancing mathematical reasoning and coding performance
of large language models (LLMs), especially when structured reference answers
are accessible for verification. However, its extension to broader, less
structured domains remains unexplored. In this work, we investigate the
effectiveness and scalability of RLVR across diverse real-world domains
including medicine, chemistry, psychology, economics, and education, where
structured reference answers are typically unavailable. We reveal that binary
verification judgments on broad-domain tasks exhibit high consistency across
various LLMs provided expert-written reference answers exist. Motivated by this
finding, we utilize a generative scoring technique that yields soft,
model-based reward signals to overcome limitations posed by binary
verifications, especially in free-form, unstructured answer scenarios. We
further demonstrate the feasibility of training cross-domain generative reward
models using relatively small (7B) LLMs without the need for extensive
domain-specific annotation. Through comprehensive experiments, our RLVR
framework establishes clear performance gains, significantly outperforming
state-of-the-art open-source aligned models such as Qwen2.5-72B and
DeepSeek-R1-Distill-Qwen-32B across domains in free-form settings. Our approach
notably enhances the robustness, flexibility, and scalability of RLVR,
representing a substantial step towards practical reinforcement learning
applications in complex, noisy-label scenarios.
