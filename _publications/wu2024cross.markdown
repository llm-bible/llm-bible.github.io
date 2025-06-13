---
layout: publication
title: 'Cross-model Control: Improving Multiple Large Language Models In One-time Training'
authors: Jiayi Wu, Hao Sun, Hengyi Cai, Lixin Su, Shuaiqiang Wang, Dawei Yin, Xiang Li, Ming Gao
conference: "Arxiv"
year: 2024
bibkey: wu2024cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17599'}
  - {name: "Code", url: 'https://github.com/wujwyi/CMC'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The number of large language models (LLMs) with varying parameter scales and
vocabularies is increasing. While they deliver powerful performance, they also
face a set of common optimization needs to meet specific requirements or
standards, such as instruction following or avoiding the output of sensitive
information from the real world. However, how to reuse the fine-tuning outcomes
of one model to other models to reduce training costs remains a challenge. To
bridge this gap, we introduce Cross-model Control (CMC), a method that improves
multiple LLMs in one-time training with a portable tiny language model.
Specifically, we have observed that the logit shift before and after
fine-tuning is remarkably similar across different models. Based on this
insight, we incorporate a tiny language model with a minimal number of
parameters. By training alongside a frozen template LLM, the tiny model gains
the capability to alter the logits output by the LLMs. To make this tiny
language model applicable to models with different vocabularies, we propose a
novel token mapping strategy named PM-MinED. We have conducted extensive
experiments on instruction tuning and unlearning tasks, demonstrating the
effectiveness of CMC. Our code is available at https://github.com/wujwyi/CMC.
