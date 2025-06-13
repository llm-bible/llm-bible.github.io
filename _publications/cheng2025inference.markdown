---
layout: publication
title: 'Biasfilter: An Inference-time Debiasing Framework For Large Language Models'
authors: Xiaoqing Cheng, Ruizhe Chen, Hongying Zan, Yuxiang Jia, Min Peng
conference: "Arxiv"
year: 2025
bibkey: cheng2025inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23829"}
tags: ['Training Techniques', 'Fairness', 'Tools', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias']
---
Mitigating social bias in large language models (LLMs) has become an increasingly important research objective. However, existing debiasing methods often incur high human and computational costs, exhibit limited effectiveness, and struggle to scale to larger models and open-ended generation tasks. To address these limitations, this paper proposes BiasFilter, a model-agnostic, inference-time debiasing framework that integrates seamlessly with both open-source and API-based LLMs. Instead of relying on retraining with balanced data or modifying model parameters, BiasFilter enforces fairness by filtering generation outputs in real time. Specifically, it periodically evaluates intermediate outputs every few tokens, maintains an active set of candidate continuations, and incrementally completes generation by discarding low-reward segments based on a fairness reward signal. To support this process, we construct a fairness preference dataset and train an implicit reward model to assess token-level fairness in generated responses. Extensive experiments demonstrate that BiasFilter effectively mitigates social bias across a range of LLMs while preserving overall generation quality.
