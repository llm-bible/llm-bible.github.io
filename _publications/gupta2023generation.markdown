---
layout: publication
title: 'Grace: Generation Using Associated Code Edits'
authors: Priyanshu Gupta, Avishree Khare, Yasharth Bajpai, Saikat Chakraborty, Sumit Gulwani, Aditya Kanade, Arjun Radhakrishna, Gustavo Soares, Ashish Tiwari
conference: "Arxiv"
year: 2023
bibkey: gupta2023generation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14129"}
tags: ['Fine-Tuning', 'Training Techniques', 'Applications', 'Pretraining Methods']
---
Developers expend a significant amount of time in editing code for a variety
of reasons such as bug fixing or adding new features. Designing effective
methods to predict code edits has been an active yet challenging area of
research due to the diversity of code edits and the difficulty of capturing the
developer intent. In this work, we address these challenges by endowing
pre-trained large language models (LLMs) of code with the knowledge of prior,
relevant edits. The generative capability of the LLMs helps address the
diversity in code changes and conditioning code generation on prior edits helps
capture the latent developer intent. We evaluate two well-known LLMs, Codex and
CodeT5, in zero-shot and fine-tuning settings respectively. In our experiments
with two datasets, the knowledge of prior edits boosts the performance of the
LLMs significantly and enables them to generate 29% and 54% more correctly
edited code in top-1 suggestions relative to the current state-of-the-art
symbolic and neural approaches, respectively.
