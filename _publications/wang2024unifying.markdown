---
layout: publication
title: 'UFT: Unifying Fine-tuning Of SFT And RLHF/DPO/UNA Through A Generalized Implicit Reward Function'
authors: Zhichao Wang, Bin Bi, Zixu Zhu, Xiangbo Mao, Jun Wang, Shiyu Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21438"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
By pretraining on trillions of tokens, an LLM gains the capability of text
generation. However, to enhance its utility and reduce potential harm, SFT and
alignment are applied sequentially to the pretrained model. Due to the
differing nature and objective functions of SFT and alignment, catastrophic
forgetting has become a significant issue. To address this, we introduce
Unified Fine-Tuning (UFT), which integrates SFT and alignment into a single
training stage using the same objective and loss functions through an implicit
reward function. Our experimental results demonstrate that UFT outperforms SFT
on instruction-tuning data alone. Moreover, when combining instruction-tuning
data with alignment data, UFT effectively prevents catastrophic forgetting
across these two stages and shows a clear advantage over sequentially applying
SFT and alignment. This is evident in the significant improvements observed in
the \textbf\{ifeval\} task for instruction-following and the \textbf\{truthful-qa\}
task for factuality. The proposed general fine-tuning framework UFT establishes
an effective and efficient pretraining-UFT paradigm for LLM training.
