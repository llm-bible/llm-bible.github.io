---
layout: publication
title: 'Decoding Knowledge In Large Language Models: A Framework For Categorization And Comprehension'
authors: Yanbo Fang, Ruixiang Tang
conference: "Arxiv"
year: 2025
bibkey: fang2025decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01332"}
tags: ['Prompting', 'Agentic', 'Tools', 'Reinforcement Learning']
---
Understanding how large language models (LLMs) acquire, retain, and apply
knowledge remains an open challenge. This paper introduces a novel framework,
K-(CSA)^2, which categorizes LLM knowledge along two dimensions: correctness
and confidence. The framework defines six categories of knowledge, ranging from
highly confident correctness to confidently held misconceptions, enabling a
nuanced evaluation of model comprehension beyond binary accuracy. Using this
framework, we demonstrate how techniques like chain-of-thought prompting and
reinforcement learning with human feedback fundamentally alter the knowledge
structures of internal (pre-trained) and external (context-dependent) knowledge
in LLMs. CoT particularly enhances base model performance and shows synergistic
benefits when applied to aligned LLMs. Moreover, our layer-wise analysis
reveals that higher layers in LLMs encode more high-confidence knowledge, while
low-confidence knowledge tends to emerge in middle-to-lower layers.
