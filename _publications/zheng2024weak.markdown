---
layout: publication
title: Weak-to-strong Extrapolation Expedites Alignment
authors: Zheng Chujie, Wang Ziqi, Ji Heng, Huang Minlie, Peng Nanyun
conference: "Arxiv"
year: 2024
bibkey: zheng2024weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16792"}
tags: ['Fine Tuning', 'Reinforcement Learning', 'Training Techniques']
---
The open-source community is experiencing a surge in the release of large language models (LLMs) that are trained to follow instructions and align with human preference. However further training to improve them still requires expensive computational resources and data annotations. Is it possible to bypass additional training and cost-effectively acquire better-aligned models Inspired by the literature on model interpolation we propose a simple method called ExPO to boost LLMs alignment with human preference. Utilizing a model that has undergone alignment training (e.g. via DPO or RLHF) and its initial SFT checkpoint ExPO directly obtains a better-aligned model by extrapolating from the weights of the initial and the aligned models which implicitly optimizes the alignment objective via first-order approximation. Through experiments with twelve open-source LLMs on HuggingFace we demonstrate that ExPO consistently improves off-the-shelf DPO/RLHF models as evaluated on the mainstream LLM benchmarks AlpacaEval 2.0 and MT-Bench. Moreover ExPO exhibits remarkable scalability across various model sizes (from 1.8B to 70B) and capabilities. Through controlled experiments and further empirical analyses we shed light on the essence of ExPO amplifying the reward signal learned during alignment training. Our work demonstrates the efficacy of model extrapolation in expediting the alignment of LLMs with human preference suggesting a promising direction for future research.
