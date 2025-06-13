---
layout: publication
title: 'Pruning Foundation Models For High Accuracy Without Retraining'
authors: Pu Zhao, Fei Sun, Xuan Shen, Pinrui Yu, Zhenglun Kong, Yanzhi Wang, Xue Lin
conference: "Arxiv"
year: 2024
bibkey: zhao2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15567"}
  - {name: "Code", url: "https://github.com/piuzha/APT"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Despite the superior performance, it is challenging to deploy foundation
models or large language models (LLMs) due to their massive parameters and
computations. While pruning is a promising technique to reduce model size and
accelerate the inference, the traditional pruning techniques can hardly be
applied for LLMs as they need to finetune the model on the full dataset with
multiple epochs consuming massive data and hardware resources. To deal with
this problem, post-training pruning methods are proposed to prune LLMs in
one-shot without retraining. However, their accuracy after pruning may suffer
from certain performance degradation due to the lack of retraining with massive
data. To address this issue, in this paper, we first formulate the
post-training problem for layer-wise LLM compression to simultaneously prune
multiple weights in LLMs. Next, we provide an optimal solution for this problem
and design our post-training pruning algorithm for both unstructured and
semi-structured sparsity. Our extensive experiments demonstrate the superior
performance of the proposed methods in comparison to SOTA baselines across
various LLM families including transformer-based LLMs and Mamba-based LLMs.
Code link: https://github.com/piuzha/APT
