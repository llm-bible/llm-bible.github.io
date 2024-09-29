---
layout: publication
title: SPEED\: Speculative Pipelined Execution For Efficient Decoding
authors: Hooper Coleman, Kim Sehoon, Mohammadzadeh Hiva, Genc Hasan, Keutzer Kurt, Gholami Amir, Shao Sophia
conference: "Arxiv"
year: 2023
bibkey: hooper2023speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12072"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Generative Large Language Models (LLMs) based on the Transformer architecture have recently emerged as a dominant foundation model for a wide range of Natural Language Processing tasks. Nevertheless their application in real-time scenarios has been highly restricted due to the significant inference latency associated with these models. This is particularly pronounced due to the autoregressive nature of generative LLM inference where tokens are generated sequentially since each token depends on all previous output tokens. It is therefore challenging to achieve any token-level parallelism making inference extremely memory-bound. In this work we propose SPEED which improves inference efficiency by speculatively executing multiple future tokens in parallel with the current token using predicted values based on early-layer hidden states. For Transformer decoders that employ parameter sharing the memory operations for the tokens executing in parallel can be amortized which allows us to accelerate generative LLM inference. We demonstrate the efficiency of our method in terms of latency reduction relative to model accuracy and demonstrate how speculation allows for training deeper decoders with parameter sharing with minimal runtime overhead.
