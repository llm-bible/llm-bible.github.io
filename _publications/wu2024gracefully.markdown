---
layout: publication
title: 'Gracefully Filtering Backdoor Samples For Generative Large Language Models Without Retraining'
authors: Zongru Wu, Pengzhou Cheng, Lingyong Fang, Zhuosheng Zhang, Gongshen Liu
conference: "Arxiv"
year: 2024
bibkey: wu2024gracefully
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02454'}
  - {name: "Code", url: 'https://github.com/ZrW00/GraceFul'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Model Architecture', 'BERT', 'Reinforcement Learning']
---
Backdoor attacks remain significant security threats to generative large
language models (LLMs). Since generative LLMs output sequences of
high-dimensional token logits instead of low-dimensional classification logits,
most existing backdoor defense methods designed for discriminative models like
BERT are ineffective for generative LLMs. Inspired by the observed differences
in learning behavior between backdoor and clean mapping in the frequency space,
we transform gradients of each training sample, directly influencing parameter
updates, into the frequency space. Our findings reveal a distinct separation
between the gradients of backdoor and clean samples in the frequency space.
Based on this phenomenon, we propose Gradient Clustering in the Frequency Space
for Backdoor Sample Filtering (GraCeFul), which leverages sample-wise gradients
in the frequency space to effectively identify backdoor samples without
requiring retraining LLMs. Experimental results show that GraCeFul outperforms
baselines significantly. Notably, GraCeFul exhibits remarkable computational
efficiency, achieving nearly 100% recall and F1 scores in identifying backdoor
samples, reducing the average success rate of various backdoor attacks to 0%
with negligible drops in clean accuracy across multiple free-style question
answering datasets. Additionally, GraCeFul generalizes to Llama-2 and Vicuna.
The codes are publicly available at https://github.com/ZrW00/GraceFul.
