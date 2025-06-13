---
layout: publication
title: 'Pruning General Large Language Models Into Customized Expert Models'
authors: Yirao Zhao, Guizhen Chen, Kenji Kawaguchi, Lidong Bing, Wenxuan Zhang
conference: "Arxiv"
year: 2025
bibkey: zhao2025pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02561"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning']
---
Large language models (LLMs) have revolutionized natural language processing, yet their substantial model sizes often require substantial computational resources. To preserve computing resources and accelerate inference speed, it is crucial to prune redundant parameters, especially for experienced users who often need compact expert models tailored to specific downstream scenarios. However, most existing pruning methods focus on preserving the model's general capabilities, often requiring extensive post-training or suffering from degraded performance due to coarse-grained pruning. In this work, we design a \\(\underline\{Cus\}\\)tom \\(\underline\{Prun\}\\)ing method (\\(\texttt\{Cus-Prun\}\\)) to prune a large general model into a smaller lightweight expert model, which is positioned along the "language", "domain" and "task" dimensions. By identifying and pruning irrelevant neurons of each dimension, \\(\texttt\{Cus-Prun\}\\) creates expert models without any post-training. Our experiments demonstrate that \\(\texttt\{Cus-Prun\}\\) consistently outperforms other methods, achieving minimal loss in both expert and general capabilities across various models from different model families and sizes.
