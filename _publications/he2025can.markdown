---
layout: publication
title: 'Can Large Language Models Detect Errors In Long Chain-of-thought Reasoning?'
authors: Yancheng He, Shilong Li, Jiaheng Liu, Weixun Wang, Xingyuan Bu, Ge Zhang, Zhongyuan Peng, Zhaoxiang Zhang, Zhicheng Zheng, Wenbo Su, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: he2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19361"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Recently, o1-like models have drawn significant attention, where these models
produce the long Chain-of-Thought (CoT) reasoning steps to improve the
reasoning abilities of existing Large Language Models (LLMs). In this paper, to
understand the qualities of these long CoTs and measure the critique abilities
of existing LLMs on these long CoTs, we introduce the DeltaBench, including the
generated long CoTs from different o1-like models (e.g., QwQ, DeepSeek-R1) for
different reasoning tasks (e.g., Math, Code, General Reasoning), to measure the
ability to detect errors in long CoT reasoning. Based on DeltaBench, we first
perform fine-grained analysis of the generated long CoTs to discover the
effectiveness and efficiency of different o1-like models. Then, we conduct
extensive evaluations of existing process reward models (PRMs) and critic
models to detect the errors of each annotated process, which aims to
investigate the boundaries and limitations of existing PRMs and critic models.
Finally, we hope that DeltaBench could guide developers to better understand
the long CoT reasoning abilities of their models.
