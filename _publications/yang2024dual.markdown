---
layout: publication
title: Dual-Phase Accelerated Prompt Optimization
authors: Yang Muchen, Li Moxin, Li Yongle, Chen Zijun, Gao Chongming, Zhang Junqi, Li Yangyang, Feng Fuli
conference: "Arxiv"
year: 2024
bibkey: yang2024dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13443"}
tags: ['Efficiency And Optimization', 'Prompting', 'RAG', 'Training Techniques']
---
Gradient-free prompt optimization methods have made significant strides in enhancing the performance of closed-source Large Language Models (LLMs) across a wide range of tasks. However existing approaches make light of the importance of high-quality prompt initialization and the identification of effective optimization directions thus resulting in substantial optimization steps to obtain satisfactory performance. In this light we aim to accelerate prompt optimization process to tackle the challenge of low convergence rate. We propose a dual-phase approach which starts with generating high-quality initial prompts by adopting a well-designed meta-instruction to delve into task-specific information and iteratively optimize the prompts at the sentence level leveraging previous tuning experience to expand prompt candidates and accept effective ones. Extensive experiments on eight datasets demonstrate the effectiveness of our proposed method achieving a consistent accuracy gain over baselines with less than five optimization steps.
