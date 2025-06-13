---
layout: publication
title: 'Modality-aware Neuron Pruning For Unlearning In Multimodal Large Language Models'
authors: Zheyuan Liu, Guangyao Dou, Xiangchi Yuan, Chunhui Zhang, Zhaoxuan Tan, Meng Jiang
conference: "Arxiv"
year: 2025
bibkey: liu2025modality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15910'}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Pruning', 'Multimodal Models']
---
Generative models such as Large Language Models (LLMs) and Multimodal Large
Language Models (MLLMs) trained on massive datasets can lead them to memorize
and inadvertently reveal sensitive information, raising ethical and privacy
concerns. While some prior works have explored this issue in the context of
LLMs, it presents a unique challenge for MLLMs due to the entangled nature of
knowledge across modalities, making comprehensive unlearning more difficult. To
address this challenge, we propose Modality Aware Neuron Unlearning (MANU), a
novel unlearning framework for MLLMs designed to selectively clip neurons based
on their relative importance to the targeted forget data, curated for different
modalities. Specifically, MANU consists of two stages: important neuron
selection and selective pruning. The first stage identifies and collects the
most influential neurons across modalities relative to the targeted forget
knowledge, while the second stage is dedicated to pruning those selected
neurons. MANU effectively isolates and removes the neurons that contribute most
to the forget data within each modality, while preserving the integrity of
retained knowledge. Our experiments conducted across various MLLM architectures
illustrate that MANU can achieve a more balanced and comprehensive unlearning
in each modality without largely affecting the overall model utility.
