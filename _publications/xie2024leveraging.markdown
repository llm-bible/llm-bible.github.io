---
layout: publication
title: 'Leveraging Human Revisions For Improving Text-to-layout Models'
authors: Xie Amber, Cheng Chin-yi, Huang Forrest, Li Yang
conference: "Arxiv"
year: 2024
bibkey: xie2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13026"}
tags: ['Agentic', 'Interpretability And Explainability', 'RAG', 'Reinforcement Learning']
---
Learning from human feedback has shown success in aligning large, pretrained models with human values. Prior works have mostly focused on learning from high-level labels, such as preferences between pairs of model outputs. On the other hand, many domains could benefit from more involved, detailed feedback, such as revisions, explanations, and reasoning of human users. Our work proposes using nuanced feedback through the form of human revisions for stronger alignment. In this paper, we ask expert designers to fix layouts generated from a generative layout model that is pretrained on a large-scale dataset of mobile screens. Then, we train a reward model based on how human designers revise these generated layouts. With the learned reward model, we optimize our model with reinforcement learning from human feedback (RLHF). Our method, Revision-Aware Reward Models (\\(\method\\)), allows a generative text-to-layout model to produce more modern, designer-aligned layouts, showing the potential for utilizing human revisions and stronger forms of feedback in improving generative models.
