---
layout: publication
title: 'Watch Every Step! LLM Agent Learning Via Iterative Step-level Process Refinement'
authors: Xiong Weimin, Song Yifan, Zhao Xiutian, Wu Wenhao, Wang Xun, Wang Ke, Li Cheng, Peng Wei, Li Sujian
conference: "Arxiv"
year: 2024
bibkey: xiong2024watch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11176"}
tags: ['Agentic', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language model agents have exhibited exceptional performance across a range of complex interactive tasks. Recent approaches have utilized tuning with expert trajectories to enhance agent performance yet they primarily concentrate on outcome rewards which may lead to errors or suboptimal actions due to the absence of process supervision signals. In this paper we introduce the Iterative step-level Process Refinement (IPR) framework which provides detailed step-by-step guidance to enhance agent training. Specifically we adopt the Monte Carlo method to estimate step-level rewards. During each iteration the agent explores along the expert trajectory and generates new actions. These actions are then evaluated against the corresponding step of expert trajectory using step-level rewards. Such comparison helps identify discrepancies yielding contrastive action pairs that serve as training data for the agent. Our experiments on three complex agent tasks demonstrate that our framework outperforms a variety of strong baselines. Moreover our analytical findings highlight the effectiveness of IPR in augmenting action efficiency and its applicability to diverse models.
