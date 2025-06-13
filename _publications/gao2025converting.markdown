---
layout: publication
title: 'Tomoe: Converting Dense Large Language Models To Mixture-of-experts Through Dynamic Structural Pruning'
authors: Shangqian Gao, Ting Hua, Reza Shirkavand, Chi-heng Lin, Zhen Tang, Zhengao Li, Longge Yuan, Fangyi Li, Zeyu Zhang, Alireza Ganjdanesh, Lou Qian, Xu Jie, Yen-chang Hsu
conference: "Arxiv"
year: 2025
bibkey: gao2025converting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.15316'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pruning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable abilities in
tackling a wide range of complex tasks. However, their huge computational and
memory costs raise significant challenges in deploying these models on
resource-constrained devices or efficiently serving them. Prior approaches have
attempted to alleviate these problems by permanently removing less important
model structures, yet these methods often result in substantial performance
degradation due to the permanent deletion of model parameters. In this work, we
tried to mitigate this issue by reducing the number of active parameters
without permanently removing them. Specifically, we introduce a differentiable
dynamic pruning method that pushes dense models to maintain a fixed number of
active parameters by converting their MLP layers into a Mixture of Experts
(MoE) architecture. Our method, even without fine-tuning, consistently
outperforms previous structural pruning techniques across diverse model
families, including Phi-2, LLaMA-2, LLaMA-3, and Qwen-2.5.
