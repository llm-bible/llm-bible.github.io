---
layout: publication
title: 'Mitigating The Alignment Tax Of RLHF'
authors: Yong Lin, Hangyu Lin, Wei Xiong, Shizhe Diao, Jianmeng Liu, Jipeng Zhang, Rui Pan, Haoxiang Wang, Wenbin Hu, Hanning Zhang, Hanze Dong, Renjie Pi, Han Zhao, Nan Jiang, Heng Ji, Yuan Yao, Tong Zhang
conference: "Arxiv"
year: 2023
bibkey: lin2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06256"}
  - {name: "Code", url: "https://github.com/avalonstrel/Mitigating-the-Alignment-Tax-of-RLHF.git"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Pre-Training']
---
LLMs acquire a wide range of abilities during pre-training, but aligning LLMs
under Reinforcement Learning with Human Feedback (RLHF) can lead to forgetting
pretrained abilities, which is also known as the alignment tax. To investigate
alignment tax, we conducted experiments with existing RLHF algorithms using
OpenLLaMA-3B, which revealed a pronounced alignment tax in NLP tasks. Whereas,
despite various techniques to mitigate forgetting, they are often at odds with
the RLHF performance, leading to a trade-off between alignment performance and
forgetting mitigation, leading to an alignment-forgetting trade-off.
  In this paper we show that model averaging, which simply interpolates between
pre and post RLHF model weights, surprisingly achieves the most strongest
alignment-forgetting Pareto front among a wide range of competing methods. To
understand its effectiveness, we offer theoretical insights into model
averaging, revealing that it enhances performance Pareto front by increasing
feature diversity on the layers where tasks share overlapped feature spaces.
Empirical evidence corroborates our analysis by showing the benefits of
averaging low-level transformer layers. Building on the analysis and the
observation that averaging different layers of the transformer leads to
significantly different alignment-forgetting trade-offs, we propose
Heterogeneous Model Averaging (HMA) to Heterogeneously find various combination
ratios of model layers. HMA seeks to maximize the alignment performance while
incurring minimal alignment tax. Moreover, we validate HMA's performance across
a range of RLHF algorithms over OpenLLaMA-3B and further extend our findings to
Mistral-7B which is evaluated by open-sourced preference model and GPT4. Code
available here:
https://github.com/avalonstrel/Mitigating-the-Alignment-Tax-of-RLHF.git.
