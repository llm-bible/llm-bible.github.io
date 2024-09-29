---
layout: publication
title: "Critic-cot: Boosting The Reasoning Abilities Of Large Language Model Via Chain-of-thoughts Critic"
authors: Zheng Xin, Lou Jie, Cao Boxi, Wen Xueru, Ji Yuqiu, Lin Hongyu, Lu Yaojie, Han Xianpei, Zhang Debing, Sun Le
conference: "Arxiv"
year: 2024
bibkey: zheng2024critic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16326"}
tags: ['Applications', 'Prompting', 'Tools', 'Training Techniques']
---
Self-critic has become an important mechanism for enhancing the reasoning performance of LLMs. However current approaches mainly involve basic prompts without further training which tend to be over-simplified leading to limited accuracy.Moreover there is a lack of in-depth investigation of the relationship between LLMs ability to criticism and its task-solving performance.To address these issues we propose Critic-CoT a novel framework that pushes LLMs toward System-2-like critic capability via step-wise CoT reasoning format and distant-supervision data construction without the need for human annotation. Experiments on GSM8K and MATH show that via filtering out invalid solutions or iterative refinement our enhanced model boosts task-solving performance which demonstrates the effectiveness of our method. Further we find that training on critique and refinement alone improves the generation. We hope our work could shed light on future research on improving the reasoning and critic ability of LLMs.
