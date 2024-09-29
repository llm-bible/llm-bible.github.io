---
layout: publication
title: Performance Law of Large Language Models
authors: Wu Chuhan, Tang Ruiming
conference: "Arxiv"
year: 2024
bibkey: wu2024performance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09895"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Guided by the belief of the scaling law large language models (LLMs) have achieved impressive performance in recent years. However scaling law only gives a qualitative estimation of loss which is influenced by various factors such as model architectures data distributions tokenizers and computation precision. Thus estimating the real performance of LLMs with different training settings rather than loss may be quite useful in practical development. In this article we present an empirical equation named Performance Law to directly predict the MMLU score of an LLM which is a widely used metric to indicate the general capability of LLMs in real-world conversations and applications. Based on only a few key hyperparameters of the LLM architecture and the size of training data we obtain a quite accurate MMLU prediction of various LLMs with diverse sizes and architectures developed by different organizations in different years. Performance law can be used to guide the choice of LLM architecture and the effective allocation of computational resources without extensive experiments.
