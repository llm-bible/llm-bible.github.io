---
layout: publication
title: Unlock The Power Competitive Distillation For Multi45;modal Large Language Models
authors: Li Xinwei, Lin Li, Wang Shuai, Qian Chen
conference: "Arxiv"
year: 2023
bibkey: li2023unlock
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08213"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Tools', 'Training Techniques']
---
Recently multi45;modal content generation has attracted lots of attention from researchers by investigating the utilization of visual instruction tuning based on large language models (LLMs). To enhance the performance and generalization ability of such LLMs the practice of distilling knowledge from pretrained multi45;modal models (a.k.a. teachers) to more compact multi45;modal LLMs (students) has gained considerable interest. However the prevailing paradigm of instructiontuning in multi45;modal LLMs knowledge distillation is resource45;intensive and unidirectional neglecting the potential for mutual feedback between the student and teacher models. Thus we propose an innovative Competitive Multi45;modal Distillation framework (CoMD) which captures bidirectional feedback between teacher and student models and continually updates the multi45;modal capabilities that the student model has learned. It comprises two stages multi45;modal pre45;training and multi45;modal competitive distillation. The first stage pre45;trains the student model on a large number of filtered multi45;modal datasets. The second stage facilitates a bidirectional knowledge transfer between the student and teacher models. Our experimental analysis of diverse datasets shows that our knowledge transfer method consistently improves the capabilities of the student model. Finally the 7B45;sized student model after four distillations surpassed the current state45;of45;the45;art model LLaVA45;13B on the ScienceQA and LLaVA Test dataset also outperforms other strong baselines in the zero45;shot setting.
