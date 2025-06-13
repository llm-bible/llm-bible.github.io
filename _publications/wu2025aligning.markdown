---
layout: publication
title: 'Aligning Llms With Domain Invariant Reward Models'
authors: David Wu, Sanjiban Choudhury
conference: "Arxiv"
year: 2025
bibkey: wu2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.00911'}
  - {name: "Code", url: 'https://github.com/portal-cornell/dial'}
tags: ['Has Code', 'Few-Shot', 'RAG', 'Tools', 'Reinforcement Learning']
---
Aligning large language models (LLMs) to human preferences is challenging in
domains where preference data is unavailable. We address the problem of
learning reward models for such target domains by leveraging feedback collected
from simpler source domains, where human preferences are easier to obtain. Our
key insight is that, while domains may differ significantly, human preferences
convey *domain-agnostic* concepts that can be effectively captured by a
reward model. We propose \method, a framework that trains domain-invariant
reward models by optimizing a dual loss: a domain loss that minimizes the
divergence between source and target distribution, and a source loss that
optimizes preferences on the source domain. We show \method is a general
approach that we evaluate and analyze across 4 distinct settings: (1)
Cross-lingual transfer (accuracy: \\(0.621 \rightarrow 0.661\\)), (2)
Clean-to-noisy (accuracy: \\(0.671 \rightarrow 0.703\\)), (3) Few-shot-to-full
transfer (accuracy: \\(0.845 \rightarrow 0.920\\)), and (4) Simple-to-complex tasks
transfer (correlation: \\(0.508 \rightarrow 0.556\\)). Our code, models and data
are available at \url\{https://github.com/portal-cornell/dial\}.
