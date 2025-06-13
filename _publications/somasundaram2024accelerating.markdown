---
layout: publication
title: 'PLD+: Accelerating LLM Inference By Leveraging Language Model Artifacts'
authors: Shwetha Somasundaram, Anirudh Phukan, Apoorv Saxena
conference: "Arxiv"
year: 2024
bibkey: somasundaram2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01447"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
To reduce the latency associated with autoretrogressive LLM inference,
speculative decoding has emerged as a novel decoding paradigm, where future
tokens are drafted and verified in parallel. However, the practical deployment
of speculative decoding is hindered by its requirements for additional
computational resources and fine-tuning, which limits its out-of-the-box
usability. To address these challenges, we present PLD+, a suite of novel
algorithms developed to accelerate the inference process of LLMs, particularly
for input-guided tasks. These tasks, which include code editing, text editing,
summarization, etc., often feature outputs with substantial overlap with their
inputs-an attribute PLD+ is designed to exploit. PLD+ also leverages the
artifacts (attention and hidden states) generated during inference to
accelerate inference speed. We test our approach on five input-guided tasks and
through extensive experiments we find that PLD+ outperforms all tuning-free
approaches. In the greedy setting, it even outperforms the state-of-the-art
tuning-dependent approach EAGLE on four of the tasks. (by a margin of upto 2.31
in terms of avg. speedup). Our approach is tuning free, does not require any
additional compute and can easily be used for accelerating inference of any
LLM.
