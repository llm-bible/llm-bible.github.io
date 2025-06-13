---
layout: publication
title: 'From Compression To Expansion: A Layerwise Analysis Of In-context Learning'
authors: Jiachen Jiang, Yuxin Dong, Jinxin Zhou, Zhihui Zhu
conference: "Arxiv"
year: 2025
bibkey: jiang2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17322"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'In-Context Learning', 'Ethics and Bias', 'Transformer', 'Prompting', 'Attention Mechanism']
---
In-context learning (ICL) enables large language models (LLMs) to adapt to new tasks without weight updates by learning from demonstration sequences. While ICL shows strong empirical performance, its internal representational mechanisms are not yet well understood. In this work, we conduct a statistical geometric analysis of ICL representations to investigate how task-specific information is captured across layers. Our analysis reveals an intriguing phenomenon, which we term *Layerwise Compression-Expansion*: early layers progressively produce compact and discriminative representations that encode task information from the input demonstrations, while later layers expand these representations to incorporate the query and generate the prediction. This phenomenon is observed consistently across diverse tasks and a range of contemporary LLM architectures. We demonstrate that it has important implications for ICL performance -- improving with model size and the number of demonstrations -- and for robustness in the presence of noisy examples. To further understand the effect of the compact task representation, we propose a bias-variance decomposition and provide a theoretical analysis showing how attention mechanisms contribute to reducing both variance and bias, thereby enhancing performance as the number of demonstrations increases. Our findings reveal an intriguing layerwise dynamic in ICL, highlight how structured representations emerge within LLMs, and showcase that analyzing internal representations can facilitate a deeper understanding of model behavior.
