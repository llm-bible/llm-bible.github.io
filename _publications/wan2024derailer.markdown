---
layout: publication
title: 'Derailer-rerailer: Adaptive Verification For Efficient And Reliable Language Model Reasoning'
authors: Guangya Wan, Yuqi Wu, Hao Wang, Shengming Zhao, Jie Chen, Sheng Li
conference: "Arxiv"
year: 2024
bibkey: wan2024derailer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13940"}
tags: ['Prompting', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown impressive reasoning capabilities,
yet existing prompting methods face a critical trade-off: simple approaches
often struggle with complex tasks and reasoning stability, while more
sophisticated methods require multiple inferences and substantial computational
resources, limiting their practical deployment. To address this challenge, we
propose Derailer-Rerailer, a novel framework that adaptively balances reasoning
accuracy and computational efficiency. At its core, our framework employs a
lightweight Derailer mechanism to assess reasoning stability and selectively
triggers an advanced Rerailer verification process only when necessary, thereby
optimizing computational resource usage. Extensive evaluation across both open
and closed-source models on more than 20 categories of mathematical, symbolic,
and commonsense reasoning tasks demonstrates our framework's effectiveness:
Derailer-Rerailer achieves significant accuracy improvements (8-11% across
various reasoning tasks) while maintaining 2-3 times better efficiency than
existing verification methods, with particularly strong performance in
mathematical and symbolic reasoning, offering a practical solution for
enhancing LLM reasoning reliability while significantly reducing computational
overhead.
