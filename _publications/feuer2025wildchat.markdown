---
layout: publication
title: 'WILDCHAT-50M: A Deep Dive Into The Role Of Synthetic Data In Post-training'
authors: Benjamin Feuer, Chinmay Hegde
conference: "Arxiv"
year: 2025
bibkey: feuer2025wildchat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18511"}
  - {name: "Code", url: "https://github.com/penfever/wildchat-50m"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Distillation']
---
Language model (LLM) post-training, from DPO to distillation, can refine behaviors and unlock new skills, but the open science supporting these post-training techniques is still in its infancy. One limiting factor has been the difficulty of conducting large-scale comparative analyses of synthetic data generating models and LLM judges. To close this gap, we introduce WILDCHAT-50M, the largest public chat dataset to date. We extend the existing WildChat dataset to include responses not only from GPT, but from over 50 different open-weight models, ranging in size from 0.5B to 104B parameters. We conduct an extensive comparative analysis and demonstrate the potential of this dataset by creating RE-WILD, our own public SFT mix, which outperforms the recent Tulu-3 SFT mixture from Allen AI with only 40% as many samples. Our dataset, samples and code are available at https://github.com/penfever/wildchat-50m.
