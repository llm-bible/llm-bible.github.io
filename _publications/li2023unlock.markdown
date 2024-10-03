---
layout: publication
title: 'Unlock The Power: Competitive Distillation For Multi-modal Large Language Models'
authors: Li Xinwei, Lin Li, Wang Shuai, Qian Chen
conference: "Arxiv"
year: 2023
bibkey: li2023unlock
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08213"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Tools', 'Training Techniques']
---
Recently, multi-modal content generation has attracted lots of attention from researchers by investigating the utilization of visual instruction tuning based on large language models (LLMs). To enhance the performance and generalization ability of such LLMs, the practice of distilling knowledge from pretrained multi-modal models (a.k.a. teachers) to more compact multi-modal LLMs (students) has gained considerable interest. However, the prevailing paradigm of instructiontuning in multi-modal LLMs knowledge distillation is resource-intensive and unidirectional, neglecting the potential for mutual feedback between the student and teacher models. Thus, we propose an innovative Competitive Multi-modal Distillation framework (CoMD), which captures bidirectional feedback between teacher and student models and continually updates the multi-modal capabilities that the student model has learned. It comprises two stages: multi-modal pre-training and multi-modal competitive distillation. The first stage pre-trains the student model on a large number of filtered multi-modal datasets. The second stage facilitates a bidirectional knowledge transfer between the student and teacher models. Our experimental analysis of diverse datasets shows that our knowledge transfer method consistently improves the capabilities of the student model. Finally, the 7B-sized student model after four distillations surpassed the current state-of-the-art model LLaVA-13B on the ScienceQA and LLaVA Test dataset, also outperforms other strong baselines in the zero-shot setting.
