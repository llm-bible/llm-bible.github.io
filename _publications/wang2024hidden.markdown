---
layout: publication
title: 'Hidden Question Representations Tell Non-factuality Within And Across Large Language Models'
authors: Wang Yanling, Li Haoyang, Zou Hao, Zhang Jing, He Xinlei, Li Qi, Xu Ke
conference: "Arxiv"
year: 2024
bibkey: wang2024hidden
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05328"}
tags: ['Fine Tuning', 'Training Techniques']
---
Despite the remarkable advance of large language models (LLMs), the
prevalence of non-factual responses remains a common issue. This work studies
non-factuality prediction (NFP), which predicts whether an LLM will generate
non-factual responses to a question before the generation process. Previous
efforts on NFP usually rely on extensive computation. In this work, we conduct
extensive analysis to explore the capabilities of using a lightweight probe to
elicit ``whether an LLM knows'' from the hidden representations of questions.
Additionally, we discover that the non-factuality probe employs similar
patterns for NFP across multiple LLMs. Motivated by the intriguing finding, we
conduct effective transfer learning for cross-LLM NFP and propose a
question-aligned strategy to ensure the efficacy of mini-batch based training.
