---
layout: publication
title: 'Stabletoolbench-mirrorapi: Modeling Tool Environments As Mirrors Of 7,000+ Real-world Apis'
authors: Zhicheng Guo, Sijie Cheng, Yuchen Niu, Hao Wang, Sicheng Zhou, Wenbing Huang, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: guo2025stabletoolbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20527"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The rapid advancement of large language models (LLMs) has spurred significant
interest in tool learning, where LLMs are augmented with external tools to
tackle complex tasks. However, existing tool environments face challenges in
balancing stability, scalability, and realness, particularly for benchmarking
purposes. To address this problem, we propose MirrorAPI, a novel framework that
trains specialized LLMs to accurately simulate real API responses, effectively
acting as "mirrors" to tool environments. Using a comprehensive dataset of
request-response pairs from 7,000+ APIs, we employ supervised fine-tuning and
chain-of-thought reasoning to enhance simulation fidelity. MirrorAPI achieves
superior accuracy and stability compared to state-of-the-art methods, as
demonstrated by its performance on the newly constructed MirrorAPI-Bench and
its integration into StableToolBench.
