---
layout: publication
title: Steering LLMs Towards Unbiased Responses A Causality-Guided Debiasing Framework
authors: Li Jingling, Tang Zeyu, Liu Xiaoyu, Spirtes Peter, Zhang Kun, Leqi Liu, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: li2024steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08743"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) can easily generate biased and discriminative responses. As LLMs tap into consequential decision-making (e.g. hiring and healthcare) it is of crucial importance to develop strategies to mitigate these biases. This paper focuses on social bias tackling the association between demographic information and LLM outputs. We propose a causality-guided debiasing framework that utilizes causal understandings of (1) the data-generating process of the training corpus fed to LLMs and (2) the internal reasoning process of LLM inference to guide the design of prompts for debiasing LLM outputs through selection mechanisms. Our framework unifies existing de-biasing prompting approaches such as inhibitive instructions and in-context contrastive examples and sheds light on new ways of debiasing by encouraging bias-free reasoning. Our strong empirical performance on real-world datasets demonstrates that our framework provides principled guidelines on debiasing LLM outputs even with only the black-box access.
