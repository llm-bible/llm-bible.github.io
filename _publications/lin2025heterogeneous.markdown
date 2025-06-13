---
layout: publication
title: 'Hsplitlora: A Heterogeneous Split Parameter-efficient Fine-tuning Framework For Large Language Models'
authors: Zheng Lin, Yuxin Zhang, Zhe Chen, Zihan Fang, Xianhao Chen, Praneeth Vepakomma, Wei Ni, Jun Luo, Yue Gao
conference: "Arxiv"
year: 2025
bibkey: lin2025heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02795"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Recently, large language models (LLMs) have achieved remarkable
breakthroughs, revolutionizing the natural language processing domain and
beyond. Due to immense parameter sizes, fine-tuning these models with private
data for diverse downstream tasks has become mainstream. Though federated
learning (FL) offers a promising solution for fine-tuning LLMs without sharing
raw data, substantial computing costs hinder its democratization. Moreover, in
real-world scenarios, private client devices often possess heterogeneous
computing resources, further complicating LLM fine-tuning. To combat these
challenges, we propose HSplitLoRA, a heterogeneous parameter-efficient
fine-tuning (PEFT) framework built on split learning (SL) and low-rank
adaptation (LoRA) fine-tuning, for efficiently fine-tuning LLMs on
heterogeneous client devices. HSplitLoRA first identifies important weights
based on their contributions to LLM training. It then dynamically configures
the decomposition ranks of LoRA adapters for selected weights and determines
the model split point according to varying computing budgets of client devices.
Finally, a noise-free adapter aggregation mechanism is devised to support
heterogeneous adapter aggregation without introducing noise. Extensive
experiments demonstrate that HSplitLoRA outperforms state-of-the-art benchmarks
in training accuracy and convergence speed.
