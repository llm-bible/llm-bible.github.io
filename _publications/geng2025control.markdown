---
layout: publication
title: 'Control Illusion: The Failure Of Instruction Hierarchies In Large Language Models'
authors: Yilin Geng, Haonan Li, Honglin Mu, Xudong Han, Timothy Baldwin, Omri Abend, Eduard Hovy, Lea Frermann
conference: "Arxiv"
year: 2025
bibkey: geng2025control
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15851"}
tags: ['Training Techniques', 'Tools', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) are increasingly deployed with hierarchical
instruction schemes, where certain instructions (e.g., system-level directives)
are expected to take precedence over others (e.g., user messages). Yet, we lack
a systematic understanding of how effectively these hierarchical control
mechanisms work. We introduce a systematic evaluation framework based on
constraint prioritization to assess how well LLMs enforce instruction
hierarchies. Our experiments across six state-of-the-art LLMs reveal that
models struggle with consistent instruction prioritization, even for simple
formatting conflicts. We find that the widely-adopted system/user prompt
separation fails to establish a reliable instruction hierarchy, and models
exhibit strong inherent biases toward certain constraint types regardless of
their priority designation. While controlled prompt engineering and model
fine-tuning show modest improvements, our results indicate that instruction
hierarchy enforcement is not robustly realized, calling for deeper
architectural innovations beyond surface-level modifications.
