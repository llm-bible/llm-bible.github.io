---
layout: publication
title: Dont Half45;listen Capturing Key45;part Information In Continual Instruction Tuning
authors: He Yongquan, Huang Xuancheng, Tang Minghao, Meng Lingxun, Li Xiang, Lin Wei, Zhang Wenyuan, Gao Yifu
conference: "Arxiv"
year: 2024
bibkey: he2024half
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10056"}
tags: ['Efficiency And Optimization', 'Training Techniques']
---
Instruction tuning for large language models (LLMs) can drive them to produce results consistent with human goals in specific downstream tasks. However the process of continual instruction tuning (CIT) for LLMs may bring about the catastrophic forgetting (CF) problem where previously learned abilities are degraded. Recent methods try to alleviate the CF problem by modifying models or replaying data which may only remember the surface45;level pattern of instructions and get confused on held45;out tasks. In this paper we propose a novel continual instruction tuning method based on Key45;part Information Gain (KPIG). Our method computes the information gain on masked parts to dynamically replay data and refine the training objective which enables LLMs to capture task45;aware information relevant to the correct response and alleviate overfitting to general descriptions in instructions. In addition we propose two metrics P45;score and V45;score to measure the generalization and instruction45;following abilities of LLMs. Experiments demonstrate our method achieves superior performance on both seen and held45;out tasks.
