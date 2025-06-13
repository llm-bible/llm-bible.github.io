---
layout: publication
title: 'Improving Token-based World Models With Parallel Observation Prediction'
authors: Lior Cohen, Kaixin Wang, Bingyi Kang, Shie Mannor
conference: "Arxiv"
year: 2024
bibkey: cohen2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05643"}
  - {name: "Code", url: "https://github.com/leor-c/REM"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Motivated by the success of Transformers when applied to sequences of
discrete symbols, token-based world models (TBWMs) were recently proposed as
sample-efficient methods. In TBWMs, the world model consumes agent experience
as a language-like sequence of tokens, where each observation constitutes a
sub-sequence. However, during imagination, the sequential token-by-token
generation of next observations results in a severe bottleneck, leading to long
training times, poor GPU utilization, and limited representations. To resolve
this bottleneck, we devise a novel Parallel Observation Prediction (POP)
mechanism. POP augments a Retentive Network (RetNet) with a novel forward mode
tailored to our reinforcement learning setting. We incorporate POP in a novel
TBWM agent named REM (Retentive Environment Model), showcasing a 15.4x faster
imagination compared to prior TBWMs. REM attains superhuman performance on 12
out of 26 games of the Atari 100K benchmark, while training in less than 12
hours. Our code is available at \url\{https://github.com/leor-c/REM\}.
