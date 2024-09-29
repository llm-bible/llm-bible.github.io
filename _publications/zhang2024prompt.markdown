---
layout: publication
title: Prompt-aware Adapter: Towards Learning Adaptive Visual Tokens For Multimodal Large Language Models
authors: Zhang Yue, Fan Hehe, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: zhang2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15684"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning']
---
To bridge the gap between vision and language modalities Multimodal Large Language Models (MLLMs) usually learn an adapter that converts visual inputs to understandable tokens for Large Language Models (LLMs). However most adapters generate consistent visual tokens regardless of the specific objects of interest mentioned in the prompt. Since these adapters distribute equal attention to every detail in the image and focus on the entire scene they may increase the cognitive load for LLMs particularly when processing complex scenes. To alleviate this problem we propose prompt-aware adapters. These adapters are designed with the capability to dynamically embed visual inputs based on the specific focus of the prompt. Specifically prompt-aware adapters utilize both global and local textual features to capture the most relevant visual clues from the prompt at both coarse and fine granularity levels. This approach significantly enhances the ability of LLMs to understand and interpret visual content. Experiments on various visual question answering tasks such as counting and position reasoning demonstrate the effectiveness of prompt-aware adapters.
