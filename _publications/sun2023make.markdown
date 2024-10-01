---
layout: publication
title: 'Make Prompt-based Black-box Tuning Colorful: Boosting Model Generalization From Three Orthogonal Perspectives'
authors: Sun Qiushi, Han Chengcheng, Chen Nuo, Zhu Renyu, Gong Jingyang, Li Xiang, Gao Ming
conference: "Arxiv"
year: 2023
bibkey: sun2023make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.08088"}
  - {name: "Code", url: "https://github.com/QiushiSun/BBT-RGB"}
tags: ['Applications', 'Efficiency And Optimization', 'Few Shot', 'Has Code', 'Prompting']
---
Large language models (LLMs) have shown increasing power on various natural language processing (NLP) tasks. However, tuning these models for downstream tasks usually needs exorbitant costs or is unavailable due to commercial considerations. Recently, black-box tuning has been proposed to address this problem by optimizing task-specific prompts without accessing the gradients and hidden representations. However, most existing works have yet fully exploited the potential of gradient-free optimization under the scenario of few-shot learning. In this paper, we describe BBT-RGB, a suite of straightforward and complementary techniques for enhancing the efficiency and performance of black-box optimization. Specifically, our method includes three plug-and-play components: (1) Two-stage derivative-free optimization strategy that facilitates fast convergence and mitigates overfitting; (2) Automatic verbalizer construction with its novel usage under few-shot settings; (3) Better prompt initialization policy based on instruction search and auto-selected demonstration. Extensive experiments across various tasks on natural language understanding and inference demonstrate the effectiveness of our method. Our codes are publicly available at https://github.com/QiushiSun/BBT-RGB.
