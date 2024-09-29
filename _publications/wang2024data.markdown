---
layout: publication
title: Inscl A Data45;efficient Continual Learning Paradigm For Fine45;tuning Large Language Models With Instructions
authors: Wang Yifan, Liu Yafei, Shi Chufan, Li Haoling, Chen Chen, Lu Haonan, Yang Yujiu
conference: "Arxiv"
year: 2024
bibkey: wang2024data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11435"}
tags: ['Applications', 'Pretraining Methods', 'Training Techniques']
---
Instruction tuning effectively optimizes Large Language Models (LLMs) for downstream tasks. Due to the changing environment in real45;life applications LLMs necessitate continual task45;specific adaptation without catastrophic forgetting. Considering the heavy computational cost replay45;based Continual Learning (CL) methods are the simplest and most widely used for LLMs to address the forgetting issue. However traditional replay45;based methods do not fully utilize instructions to customize the replay strategy. In this work we propose a novel paradigm called Instruction45;based Continual Learning (InsCL). InsCL dynamically replays previous data based on task similarity calculated by Wasserstein Distance with instructions. Moreover we further introduce an Instruction Information Metric (InsInfo) to quantify the complexity and diversity of instructions. According to InsInfo InsCL guides the replay process more inclined to high45;quality data. We conduct extensive experiments over 16 tasks with different training orders observing consistent performance improvements of InsCL. When all tasks have been trained InsCL achieves performance gains of 3.0 Relative Gain compared with Random Replay and 27.96 Relative Gain compared with No Replay.
