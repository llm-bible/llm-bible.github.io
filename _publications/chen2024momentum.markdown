---
layout: publication
title: 'Mofo: Momentum-filtered Optimizer For Mitigating Forgetting In LLM Fine-tuning'
authors: Yupeng Chen, Senmiao Wang, Yushun Zhang, Zhihang Lin, Haozhe Zhang, Weijian Sun, Tian Ding, Ruoyu Sun
conference: "Arxiv"
year: 2024
bibkey: chen2024momentum
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20999"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Large language models (LLMs) have demonstrated remarkable capabilities across
a wide range of tasks. Typically, LLMs are first pre-trained on large corpora
and subsequently fine-tuned on task-specific datasets. However, during
fine-tuning, LLMs may forget some knowledge acquired in the pre-training stage,
leading to a decline in general capabilities. Existing approaches to mitigate
forgetting often rely on access to pre-training data, which may be unavailable
in many real-world scenarios--such as fine-tuning checkpoint-only open-source
LLMs. To address this challenge, we propose a new fine-tuning algorithm termed
Momentum-Filtered Optimizer (MoFO). MoFO is an extension of greedy block
coordinate descent (BCD) methods: in each iteration, MoFO only updates the
model parameters with the largest momentum magnitudes, while keeping all other
parameters fixed. MoFO achieves similar fine-tuning performance to the default
fine-tuning algorithm while effectively mitigating knowledge forgetting. We
validate MoFO through rigorous convergence analysis and extensive experiments,
demonstrating its effectiveness in mitigating forgetting without pre-training
data.
