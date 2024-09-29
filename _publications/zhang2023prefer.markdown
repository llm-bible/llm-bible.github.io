---
layout: publication
title: PREFER Prompt Ensemble Learning via Feedback-Reflect-Refine
authors: Zhang Chenrui, Liu Lin, Wang Jinpeng, Wang Chuyuan, Sun Xiao, Wang Hongyu, Cai Mingchen
conference: "Arxiv"
year: 2023
bibkey: zhang2023prefer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12033"}
tags: ['Efficiency And Optimization', 'Prompting', 'Reinforcement Learning']
---
As an effective tool for eliciting the power of Large Language Models (LLMs) prompting has recently demonstrated unprecedented abilities across a variety of complex tasks. To further improve the performance prompt ensemble has attracted substantial interest for tackling the hallucination and instability of LLMs. However existing methods usually adopt a two-stage paradigm which requires a pre-prepared set of prompts with substantial manual effort and is unable to perform directed optimization for different weak learners. In this paper we propose a simple universal and automatic method named PREFER (Pompt Ensemble learning via Feedback-Reflect-Refine) to address the stated limitations. Specifically given the fact that weak learners are supposed to focus on hard examples during boosting PREFER builds a feedback mechanism for reflecting on the inadequacies of existing weak learners. Based on this the LLM is required to automatically synthesize new prompts for iterative refinement. Moreover to enhance stability of the prompt effect evaluation we propose a novel prompt bagging method involving forward and backward thinking which is superior to majority voting and is beneficial for both feedback and weight calculation in boosting. Extensive experiments demonstrate that our PREFER achieves state-of-the-art performance in multiple types of tasks by a significant margin. We have made our code publicly available.
