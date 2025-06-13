---
layout: publication
title: 'Privacyscalpel: Enhancing LLM Privacy Via Interpretable Feature Intervention With Sparse Autoencoders'
authors: Ahmed Frikha, Muhammad Reza Ar Razi, Krishna Kanth Nakka, Ricardo Mendes, Xue Jiang, Xuebing Zhou
conference: "Arxiv"
year: 2025
bibkey: frikha2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.11232'}
tags: ['Interpretability and Explainability', 'RAG', 'Security', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
natural language processing but also pose significant privacy risks by
memorizing and leaking Personally Identifiable Information (PII). Existing
mitigation strategies, such as differential privacy and neuron-level
interventions, often degrade model utility or fail to effectively prevent
leakage. To address this challenge, we introduce PrivacyScalpel, a novel
privacy-preserving framework that leverages LLM interpretability techniques to
identify and mitigate PII leakage while maintaining performance. PrivacyScalpel
comprises three key steps: (1) Feature Probing, which identifies layers in the
model that encode PII-rich representations, (2) Sparse Autoencoding, where a
k-Sparse Autoencoder (k-SAE) disentangles and isolates privacy-sensitive
features,
  and (3) Feature-Level Interventions, which employ targeted ablation and
vector steering to suppress PII leakage.
  Our empirical evaluation on Gemma2-2b and Llama2-7b, fine-tuned on the Enron
dataset, shows that PrivacyScalpel significantly reduces email leakage from
5.15% to as low as 0.0%, while maintaining over 99.4% of the original
model's utility. Notably, our method outperforms neuron-level interventions in
privacy-utility trade-offs, demonstrating that acting on sparse, monosemantic
features is more effective than manipulating polysemantic neurons. Beyond
improving LLM privacy, our approach offers insights into the mechanisms
underlying PII memorization, contributing to the broader field of model
interpretability and secure AI deployment.
