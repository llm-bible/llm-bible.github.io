---
layout: publication
title: 'RAISE: Reinforced Adaptive Instruction Selection For Large Language Models'
authors: Lv Qingsong, Yangning Li, Zihua Lan, Zishan Xu, Jiwei Tang, Yinghui Li, Wenhao Jiang, Hai-tao Zheng, Philip S. Yu
conference: "Arxiv"
year: 2025
bibkey: qingsong2025reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07282"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
In the instruction fine-tuning of large language models (LLMs), it is widely recognized that a few high-quality instructions are superior to a large number of low-quality instructions. At present, many instruction selection methods have been proposed, but most of these methods select instruction based on heuristic quality metrics, and only consider data selection before training. These designs lead to insufficient optimization of instruction fine-tuning, and fixed heuristic indicators are often difficult to optimize for specific tasks. Therefore, we design a dynamic, task-objective-driven instruction selection framework RAISE(Reinforced Adaptive Instruction SElection), which incorporates the entire instruction fine-tuning process into optimization, selecting instructions at each step based on the expected impact of each instruction on model performance improvement. Our approach is well interpretable and has strong task-specific optimization capabilities. By modeling dynamic instruction selection as a sequential decision-making process, we use RL to train our selection strategy. Extensive experiments and result analysis prove the superiority of our method compared with other instruction selection methods. Notably, RAISE achieves superior performance by updating only 1% of the training steps compared to full-data training, demonstrating its efficiency and effectiveness.
