---
layout: publication
title: 'Process Or Result? Manipulated Ending Tokens Can Mislead Reasoning Llms To Ignore The Correct Reasoning Steps'
authors: Yu Cui, Bryan Hooi, Yujun Cai, Yiwei Wang
conference: "Arxiv"
year: 2025
bibkey: cui2025process
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19326'}
tags: ['Fine-Tuning', 'Security', 'Prompting', 'Applications']
---
Recent reasoning large language models (LLMs) have demonstrated remarkable
improvements in mathematical reasoning capabilities through long
Chain-of-Thought. The reasoning tokens of these models enable self-correction
within reasoning chains, enhancing robustness. This motivates our exploration:
how vulnerable are reasoning LLMs to subtle errors in their input reasoning
chains? We introduce "Compromising Thought" (CPT), a vulnerability where models
presented with reasoning tokens containing manipulated calculation results tend
to ignore correct reasoning steps and adopt incorrect results instead. Through
systematic evaluation across multiple reasoning LLMs, we design three
increasingly explicit prompting methods to measure CPT resistance, revealing
that models struggle significantly to identify and correct these manipulations.
Notably, contrary to existing research suggesting structural alterations affect
model performance more than content modifications, we find that local ending
token manipulations have greater impact on reasoning outcomes than structural
changes. Moreover, we discover a security vulnerability in DeepSeek-R1 where
tampered reasoning tokens can trigger complete reasoning cessation. Our work
enhances understanding of reasoning robustness and highlights security
considerations for reasoning-intensive applications.
