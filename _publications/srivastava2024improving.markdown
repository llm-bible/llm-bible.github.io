---
layout: publication
title: 'Improving Multimodal Large Language Models Using Continual Learning'
authors: Shikhar Srivastava, Md Yousuf Harun, Robik Shrestha, Christopher Kanan
conference: "Arxiv"
year: 2024
bibkey: srivastava2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19925"}
tags: ['Security', 'Applications', 'Multimodal Models']
---
Generative large language models (LLMs) exhibit impressive capabilities,
which can be further augmented by integrating a pre-trained vision model into
the original LLM to create a multimodal LLM (MLLM). However, this integration
often significantly decreases performance on natural language understanding and
generation tasks, compared to the original LLM. This study investigates this
issue using the LLaVA MLLM, treating the integration as a continual learning
problem. We evaluate five continual learning methods to mitigate forgetting and
identify a technique that enhances visual understanding while minimizing
linguistic performance loss. Our approach reduces linguistic performance
degradation by up to 15% over the LLaVA recipe, while maintaining high
multimodal accuracy. We also demonstrate the robustness of our method through
continual learning on a sequence of vision-language tasks, effectively
preserving linguistic skills while acquiring new multimodal capabilities.
