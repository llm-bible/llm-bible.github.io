---
layout: publication
title: QADYNAMICS\: Training Dynamics-driven Synthetic QA Diagnostic For Zero-shot Commonsense Question Answering
authors: Shi Haochen, Wang Weiqi, Fang Tianqing, Xu Baixuan, Ding Wenxuan, Liu Xin, Song Yangqiu
conference: "Arxiv"
year: 2023
bibkey: shi2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11303"}
  - {name: "Code", url: "https://github.com/HKUST-KnowComp/QaDynamics"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Tools', 'Training Techniques']
---
Zero-shot commonsense Question-Answering (QA) requires models to reason about general situations beyond specific benchmarks. State-of-the-art approaches fine-tune language models on QA pairs constructed from CommonSense Knowledge Bases (CSKBs) to equip the models with more commonsense knowledge in a QA context. However current QA synthesis protocols may introduce noise from the CSKBs and generate ungrammatical questions and false negative options which impede the models ability to generalize. To address these issues we propose QADYNAMICS a training dynamics-driven framework for QA diagnostics and refinement. Our approach analyzes the training dynamics of each QA pair at both the question level and option level discarding machine-detectable artifacts by removing uninformative QA pairs and mislabeled or false-negative options. Extensive experiments demonstrate the effectiveness of our approach which outperforms all baselines while using only 3337; of the synthetic data even including LLMs such as ChatGPT. Moreover expert evaluations confirm that our framework significantly improves the quality of QA synthesis. Our codes and model checkpoints are available at https://github.com/HKUST-KnowComp/QaDynamics."
