---
layout: publication
title: Auto45;encoding Morph45;tokens For Multimodal LLM
authors: Pan Kaihang, Tang Siliang, Li Juncheng, Fan Zhaoyu, Chow Wei, Yan Shuicheng, Chua Tat-seng, Zhuang Yueting, Zhang Hanwang
conference: "Arxiv"
year: 2024
bibkey: pan2024auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01926"}
  - {name: "Code", url: "https://github.com/DCDmllm/MorphTokens"}
tags: ['Has Code', 'Multimodal Models', 'Prompting']
---
For multimodal LLMs the synergy of visual comprehension (textual output) and generation (visual output) presents an ongoing challenge. This is due to a conflicting objective for comprehension an MLLM needs to abstract the visuals; for generation it needs to preserve the visuals as much as possible. Thus the objective is a dilemma for visual45;tokens. To resolve the conflict we propose encoding images into morph45;tokens to serve a dual purpose for comprehension they act as visual prompts instructing MLLM to generate texts; for generation they take on a different non45;conflicting role as complete visual45;tokens for image reconstruction where the missing visual cues are recovered by the MLLM. Extensive experiments show that morph45;tokens can achieve a new SOTA for multimodal comprehension and generation simultaneously. Our project is available at https://github.com/DCDmllm/MorphTokens.
