---
layout: publication
title: 'Crystal: Illuminating LLM Abilities On Language And Code'
authors: Tianhua Tao, Junbo Li, Bowen Tan, Hongyi Wang, William Marshall, Bhargav M Kanakiya, Joel Hestness, Natalia Vassilieva, Zhiqiang Shen, Eric P. Xing, Zhengzhong Liu
conference: "Arxiv"
year: 2024
bibkey: tao2024illuminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04156"}
tags: ['Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) specializing in code generation (which are also
often referred to as code LLMs), e.g., StarCoder and Code Llama, play
increasingly critical roles in various software development scenarios. It is
also crucial for code LLMs to possess both code generation and natural language
abilities for many specific applications, such as code snippet retrieval using
natural language or code explanations. The intricate interaction between
acquiring language and coding skills complicates the development of strong code
LLMs. Furthermore, there is a lack of thorough prior studies on the LLM
pretraining strategy that mixes code and natural language. In this work, we
propose a pretraining strategy to enhance the integration of natural language
and coding capabilities within a single LLM. Specifically, it includes two
phases of training with appropriately adjusted code/language ratios. The
resulting model, Crystal, demonstrates remarkable capabilities in both domains.
Specifically, it has natural language and coding performance comparable to that
of Llama 2 and Code Llama, respectively. Crystal exhibits better data
efficiency, using 1.4 trillion tokens compared to the more than 2 trillion
tokens used by Llama 2 and Code Llama. We verify our pretraining strategy by
analyzing the training process and observe consistent improvements in most
benchmarks. We also adopted a typical application adaptation phase with a
code-centric data mixture, only to find that it did not lead to enhanced
performance or training efficiency, underlining the importance of a carefully
designed data recipe. To foster research within the community, we commit to
open-sourcing every detail of the pretraining, including our training datasets,
code, loggings and 136 checkpoints throughout the training.
