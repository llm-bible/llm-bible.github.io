---
layout: publication
title: 'Enhancing Visual Grounding For GUI Agents Via Self-evolutionary Reinforcement Learning'
authors: Xinbin Yuan, Jian Zhang, Kaixin Li, Zhuoxuan Cai, Lujian Yao, Jie Chen, Enguang Wang, Qibin Hou, Jinwei Chen, Peng-tao Jiang, Bo Li
conference: "Arxiv"
year: 2025
bibkey: yuan2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12370"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Attention Mechanism']
---
Graphical User Interface (GUI) agents have made substantial strides in understanding and executing user instructions across diverse platforms. Yet, grounding these instructions to precise interface elements remains challenging, especially in complex, high-resolution, professional environments. Traditional supervised finetuning (SFT) methods often require large volumes of diverse data and exhibit weak generalization. To overcome these limitations, we introduce a reinforcement learning (RL) based framework that incorporates three core strategies: (1) seed data curation to ensure high quality training samples, (2) a dense policy gradient that provides continuous feedback based on prediction accuracy, and (3) a self evolutionary reinforcement finetuning mechanism that iteratively refines the model using attention maps. With only 3k training samples, our 7B-parameter model achieves state-of-the-art results among similarly sized models on three grounding benchmarks. Notably, it attains 47.3% accuracy on the ScreenSpot-Pro dataset, outperforming much larger models, such as UI-TARS-72B, by a margin of 24.2%. These findings underscore the effectiveness of RL-based approaches in enhancing GUI agent performance, particularly in high-resolution, complex environments.
