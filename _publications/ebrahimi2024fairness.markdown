---
layout: publication
title: 'AXOLOTL: Fairness Through Assisted Self-debiasing Of Large Language Model Outputs'
authors: Ebrahimi Sana, Chen Kaiwen, Asudeh Abolfazl, Das Gautam, Koudas Nick
conference: "Arxiv"
year: 2024
bibkey: ebrahimi2024fairness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00198"}
tags: ['Applications', 'Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Fine Tuning', 'RAG', 'Tools', 'Training Techniques']
---
Pre-trained Large Language Models (LLMs) have significantly advanced natural language processing capabilities but are susceptible to biases present in their training data, leading to unfair outcomes in various applications. While numerous strategies have been proposed to mitigate bias, they often require extensive computational resources and may compromise model performance. In this work, we introduce AXOLOTL, a novel post-processing framework, which operates agnostically across tasks and models, leveraging public APIs to interact with LLMs without direct access to internal parameters. Through a three-step process resembling zero-shot learning, AXOLOTL identifies biases, proposes resolutions, and guides the model to self-debias its outputs. This approach minimizes computational costs and preserves model performance, making AXOLOTL a promising tool for debiasing LLM outputs with broad applicability and ease of use.
