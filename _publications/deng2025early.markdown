---
layout: publication
title: 'Openvlthinker: An Early Exploration To Complex Vision-language Reasoning Via Iterative Self-improvement'
authors: Yihe Deng, Hritik Bansal, Fan Yin, Nanyun Peng, Wei Wang, Kai-wei Chang
conference: "Arxiv"
year: 2025
bibkey: deng2025early
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17352'}
  - {name: "Code", url: 'https://github.com/yihedeng9/OpenVLThinker'}
tags: ['Agentic', 'Has Code', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements demonstrated by DeepSeek-R1 have shown that complex
reasoning abilities in large language models (LLMs), including sophisticated
behaviors such as self-verification and self-correction, can be achieved by RL
with verifiable rewards and significantly improves model performance on
challenging tasks such as AIME. Motivated by these findings, our study
investigates whether similar reasoning capabilities can be successfully
integrated into large vision-language models (LVLMs) and assesses their impact
on challenging multimodal reasoning tasks. We consider an approach that
iteratively leverages supervised fine-tuning (SFT) on lightweight training data
and Reinforcement Learning (RL) to further improve model generalization.
Initially, reasoning capabilities were distilled from pure-text R1 models by
generating reasoning steps using high-quality captions of the images sourced
from diverse visual datasets. Subsequently, iterative RL training further
enhance reasoning skills, with each iteration's RL-improved model generating
refined SFT datasets for the next round. This iterative process yielded
OpenVLThinker, a LVLM exhibiting consistently improved reasoning performance on
challenging benchmarks such as MathVista, MathVerse, and MathVision,
demonstrating the potential of our strategy for robust vision-language
reasoning. The code, model and data are held at
https://github.com/yihedeng9/OpenVLThinker.
