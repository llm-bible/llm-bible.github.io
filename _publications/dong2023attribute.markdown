---
layout: publication
title: 'Steerlm: Attribute Conditioned SFT As An (user-steerable) Alternative To RLHF'
authors: Yi Dong, Zhilin Wang, Makesh Narsimhan Sreedhar, Xianchao Wu, Oleksii Kuchaiev
conference: "Arxiv"
year: 2023
bibkey: dong2023attribute
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05344"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Model alignment with human preferences is an essential step in making Large
Language Models (LLMs) helpful and consistent with human values. It typically
consists of supervised fine-tuning (SFT) and reinforcement learning from human
feedback (RLHF) stages. However, RLHF faces inherent limitations stemming from
a complex training setup and its tendency to align the model with implicit
values that end users cannot control at run-time. Moreover, reward models in
RLHF stage commonly rely on single-dimensional feedback as opposed to explicit,
multifaceted signals that indicate attributes such as helpfulness, humor, and
toxicity. To address these limitations, we propose SteerLM, a supervised
fine-tuning method that empowers end-users to control responses during
inference. SteerLM conditions responses to conform to an explicitly defined
multi-dimensional set of attributes, thereby empowering a steerable AI capable
of generating helpful and high-quality responses while maintaining
customizability. Experiments show that SteerLM trained on open source datasets
generates responses that are preferred by human and automatic evaluators to
many state-of-the-art baselines trained with RLHF while being much easier to
train. Try SteerLM at https://huggingface.co/nvidia/SteerLM-llama2-13B
