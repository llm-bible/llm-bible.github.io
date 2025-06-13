---
layout: publication
title: 'Establishing Trustworthy LLM Evaluation Via Shortcut Neuron Analysis'
authors: Kejian Zhu, Shangqing Tu, Zhuoran Jin, Lei Hou, Juanzi Li, Jun Zhao
conference: "Arxiv"
year: 2025
bibkey: zhu2025establishing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04142"}
  - {name: "Code", url: "https://github.com/GaryStack/Trustworthy-Evaluation"}
tags: ['Ethics and Bias', 'Bias Mitigation', 'Training Techniques', 'Has Code', 'Fairness']
---
The development of large language models (LLMs) depends on trustworthy evaluation. However, most current evaluations rely on public benchmarks, which are prone to data contamination issues that significantly compromise fairness. Previous researches have focused on constructing dynamic benchmarks to address contamination. However, continuously building new benchmarks is costly and cyclical. In this work, we aim to tackle contamination by analyzing the mechanisms of contaminated models themselves. Through our experiments, we discover that the overestimation of contaminated models is likely due to parameters acquiring shortcut solutions in training. We further propose a novel method for identifying shortcut neurons through comparative and causal analysis. Building on this, we introduce an evaluation method called shortcut neuron patching to suppress shortcut neurons. Experiments validate the effectiveness of our approach in mitigating contamination. Additionally, our evaluation results exhibit a strong linear correlation with MixEval, a recently released trustworthy benchmark, achieving a Spearman coefficient (\\(\rho\\)) exceeding 0.95. This high correlation indicates that our method closely reveals true capabilities of the models and is trustworthy. We conduct further experiments to demonstrate the generalizability of our method across various benchmarks and hyperparameter settings. Code: https://github.com/GaryStack/Trustworthy-Evaluation
