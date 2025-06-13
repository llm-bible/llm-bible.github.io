---
layout: publication
title: 'ROSE: A Reward-oriented Data Selection Framework For LLM Task-specific Instruction Tuning'
authors: Yang Wu, Huayi Zhang, Yizheng Jiao, Lin Ma, Xiaozhong Liu, Jinhong Yu, Dongyu Zhang, Dezhi Yu, Wei Xu
conference: "Arxiv"
year: 2024
bibkey: wu2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00631"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Instruction tuning has underscored the significant potential of large
language models (LLMs) in producing more human-controllable and effective
outputs in various domains. In this work, we focus on the data selection
problem for task-specific instruction tuning of LLMs. Prevailing methods
primarily rely on the crafted similarity metrics to select training data that
aligns with the test data distribution. The goal is to minimize instruction
tuning loss on the test data, ultimately improving performance on the target
task. However, it has been widely observed that instruction tuning loss (i.e.,
cross-entropy loss for next token prediction) in LLMs often fails to exhibit a
monotonic relationship with actual task performance. This misalignment
undermines the effectiveness of current data selection methods for
task-specific instruction tuning. To address this issue, we introduce ROSE, a
novel Reward-Oriented inStruction data sElection method which leverages
pairwise preference loss as a reward signal to optimize data selection for
task-specific instruction tuning. Specifically, ROSE adapts an influence
formulation to approximate the influence of training data points relative to a
few-shot preference validation set to select the most task-related training
data points. Experimental results show that by selecting just 5% of the
training data using ROSE, our approach can achieve competitive results compared
to fine-tuning with the full training dataset, and it surpasses other
state-of-the-art data selection methods for task-specific instruction tuning.
Our qualitative analysis further confirms the robust generalizability of our
method across multiple benchmark datasets and diverse model architectures.
