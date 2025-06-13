---
layout: publication
title: 'Fighting Fire With Fire (F3): A Training-free And Efficient Visual Adversarial Example Purification Method In Lvlms'
authors: Yudong Zhang, Ruobing Xie, Yiqing Huang, Jiansheng Chen, Xingwu Sun, Zhanhui Kang, Di Wang, Yu Wang
conference: "Arxiv"
year: 2025
bibkey: zhang2025fighting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01064"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'RAG', 'Applications', 'Attention Mechanism']
---
Recent advances in large vision-language models (LVLMs) have showcased their remarkable capabilities across a wide range of multimodal vision-language tasks. However, these models remain vulnerable to visual adversarial attacks, which can substantially compromise their performance. Despite their potential impact, the development of effective methods for purifying such adversarial examples has received relatively limited attention. In this paper, we introduce F3, a novel adversarial purification framework that employs a counterintuitive "fighting fire with fire" strategy: intentionally introducing simple perturbations to adversarial examples to mitigate their harmful effects. Specifically, F3 leverages cross-modal attentions derived from randomly perturbed adversary examples as reference targets. By injecting noise into these adversarial examples, F3 effectively refines their attention, resulting in cleaner and more reliable model outputs. Remarkably, this seemingly paradoxical approach of employing noise to counteract adversarial attacks yields impressive purification results. Furthermore, F3 offers several distinct advantages: it is training-free and straightforward to implement, and exhibits significant computational efficiency improvements compared to existing purification methods. These attributes render F3 particularly suitable for large-scale industrial applications where both robust performance and operational efficiency are critical priorities. The code will be made publicly available.
