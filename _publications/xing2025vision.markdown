---
layout: publication
title: 'Vision-centric Token Compression In Large Language Model'
authors: Ling Xing, Alex Jinpeng Wang, Rui Yan, Xiangbo Shu, Jinhui Tang
conference: "Arxiv"
year: 2025
bibkey: xing2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00791"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Real-world applications are stretching context windows to hundreds of thousand of tokens while Large Language Models (LLMs) swell from billions to trillions of parameters. This dual expansion send compute and memory costs skyrocketing, making token compression indispensable. We introduce Vision Centric Token Compression (Vist), a slow-fast compression framework that mirrors human reading: the fast path renders distant tokens into images, letting a frozen, lightweight vision encoder skim the low-salience context; the slow path feeds the proximal window into the LLM for fine-grained reasoning. A Probability-Informed Visual Enhancement (PVE) objective masks high-frequency tokens during training, steering the Resampler to concentrate on semantically rich regions-just as skilled reader gloss over function words. On eleven in-context learning benchmarks, Vist achieves the same accuracy with 2.3 times fewer tokens, cutting FLOPs by 16% and memory by 50%. This method delivers remarkable results, outperforming the strongest text encoder-based compression method CEPE by 7.6% on average over benchmarks like TriviaQA, NQ, PopQA, NLUI, and CLIN, setting a new standard for token efficiency in LLMs. The source code will be released.
