---
layout: publication
title: 'Distillation And Refinement Of Reasoning In Small Language Models For Document Re-ranking'
authors: Chris Samarinas, Hamed Zamani
conference: "Arxiv"
year: 2025
bibkey: samarinas2025distillation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03947"}
tags: ['Agentic', 'Efficiency and Optimization', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
We present a novel approach for training small language models for
reasoning-intensive document ranking that combines knowledge distillation with
reinforcement learning optimization. While existing methods often rely on
expensive human annotations or large black-box language models, our methodology
leverages web data and a teacher LLM to automatically generate high-quality
training examples with relevance explanations. By framing document ranking as a
reinforcement learning problem and incentivizing explicit reasoning
capabilities, we train a compact 3B parameter language model that achieves
state-of-the-art performance on the BRIGHT benchmark. Our model ranks third on
the leaderboard while using substantially fewer parameters than other
approaches, outperforming models that are over 20 times larger. Through
extensive experiments, we demonstrate that generating explanations during
inference, rather than directly predicting relevance scores, enables more
effective reasoning with smaller language models. The self-supervised nature of
our method offers a scalable and interpretable solution for modern information
retrieval systems.
