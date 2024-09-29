---
layout: publication
title: "On The Efficacy Of Eviction Policy For Key-value Constrained Generative Language Model Inference"
authors: Ren Siyu, Zhu Kenny Q.
conference: "Arxiv"
year: 2024
bibkey: ren2024efficacy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06262"}
  - {name: "Code", url: "https://github.com/DRSY/EasyKV"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security']
---
Despite the recent success associated with Large Language Models (LLMs) they are notably cost-prohibitive to deploy in resource-constrained environments due to their excessive memory and computational demands. In addition to model parameters the key-value cache is also stored in GPU memory growing linearly with batch size and sequence length. As a remedy recent works have proposed various eviction policies for maintaining the overhead of key-value cache under a given budget. This paper embarks on the efficacy of existing eviction policies in terms of importance score calculation and eviction scope construction. We identify the deficiency of prior policies in these two aspects and introduce RoCo a robust cache omission policy based on temporal attention scores and robustness measures. Extensive experimentation spanning prefilling and auto-regressive decoding stages validates the superiority of RoCo. Finally we release EasyKV a versatile software package dedicated to user-friendly key-value constrained generative inference. Code available at https://github.com/DRSY/EasyKV."
