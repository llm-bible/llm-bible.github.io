---
layout: publication
title: 'Model-based Large Language Model Customization As Service'
authors: Zhaomin Wu, Jizhou Guo, Junyi Hou, Bingsheng He, Lixin Fan, Qiang Yang
conference: "Arxiv"
year: 2024
bibkey: wu2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10481"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Prominent Large Language Model (LLM) services from providers like OpenAI and Google excel at general tasks but often underperform on domain-specific applications. Current customization services for these LLMs typically require users to upload data for fine-tuning, posing significant privacy risks. While differentially private (DP) data synthesis presents a potential alternative, its application commonly results in low effectiveness due to the introduction of excessive noise on data for DP. To overcome this, we introduce Llamdex, a novel framework that facilitates LLM customization as a service, where the client uploads pre-trained domain-specific models rather than data. This client-uploaded model, optionally protected by DP with much lower noise, is inserted into the base LLM via connection modules. Significantly, these connecting modules are trained without requiring sensitive domain data, enabling clients to customize LLM services while preserving data privacy. Experiments demonstrate that Llamdex improves domain-specific accuracy by up to 26% over state-of-the-art private data synthesis methods under identical privacy constraints and, by obviating the need for users to provide domain context within queries, maintains inference efficiency comparable to the original LLM service.
