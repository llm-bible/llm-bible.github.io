---
layout: publication
title: 'Mitigating Selection Bias With Node Pruning And Auxiliary Options'
authors: Hyeong Kyu Choi, Weijie Xu, Chi Xue, Stephanie Eckman, Chandan K. Reddy
conference: "Arxiv"
year: 2024
bibkey: choi2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18857"}
tags: ['Ethics and Bias', 'Efficiency and Optimization', 'Applications', 'Pruning']
---
Large language models (LLMs) often exhibit systematic preferences for certain answer choices when responding to multiple-choice questions-a behavior known as selection bias. This bias reduces the accuracy and reliability of LLM outputs, limiting their usefulness in decision-critical applications. While prior work has focused on adjusting model inputs or outputs to mitigate this issue, our work takes a fundamentally different approach by identifying and removing the internal sources of bias. We introduce two methods: Bias Node Pruning (BNP), which prunes parameters that contribute to selection bias, and Auxiliary Option Injection (AOI), which introduces an additional answer choice to reduce bias in both white-box and black-box settings. To address the shortcomings of existing evaluation metrics, we propose Choice Kullback-Leibler Divergence (CKLD), a new metric that captures distributional imbalances in model predictions. Experiments on three LLMs across multiple datasets demonstrate that our methods consistently improve answer accuracy while reducing selection bias, providing a robust solution for both open- and closed-source models.
