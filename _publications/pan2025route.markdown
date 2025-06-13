---
layout: publication
title: 'Route To Reason: Adaptive Routing For LLM And Reasoning Strategy Selection'
authors: Zhihong Pan, Kai Zhang, Yuze Zhao, Yupeng Han
conference: "Arxiv"
year: 2025
bibkey: pan2025route
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19435"}
tags: ['Tools', 'Efficiency and Optimization']
---
The inherent capabilities of a language model (LM) and the reasoning strategies it employs jointly determine its performance in reasoning tasks. While test-time scaling is regarded as an effective approach to tackling complex reasoning tasks, it incurs substantial computational costs and often leads to "overthinking", where models become trapped in "thought pitfalls". To address this challenge, we propose Route-To-Reason (RTR), a novel unified routing framework that dynamically allocates both LMs and reasoning strategies according to task difficulty under budget constraints. RTR learns compressed representations of both expert models and reasoning strategies, enabling their joint and adaptive selection at inference time. This method is low-cost, highly flexible, and can be seamlessly extended to arbitrary black-box or white-box models and strategies, achieving true plug-and-play functionality. Extensive experiments across seven open source models and four reasoning strategies demonstrate that RTR achieves an optimal trade-off between accuracy and computational efficiency among all baselines, achieving higher accuracy than the best single model while reducing token usage by over 60%.
