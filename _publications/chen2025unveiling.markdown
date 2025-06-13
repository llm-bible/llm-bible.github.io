---
layout: publication
title: 'Unveiling The Key Factors For Distilling Chain-of-thought Reasoning'
authors: Xinghao Chen, Zhijing Sun, Wenjin Guo, Miaoran Zhang, Yanjun Chen, Yirong Sun, Hui Su, Yijie Pan, Dietrich Klakow, Wenjie Li, Xiaoyu Shen
conference: "Arxiv"
year: 2025
bibkey: chen2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18001"}
  - {name: "Code", url: "https://github.com/EIT-NLP/Distilling-CoT-Reasoning"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'Distillation']
---
Large Language Models (LLMs) excel in reasoning tasks through Chain-of-Thought (CoT) prompting. However, CoT prompting greatly increases computational demands, which has prompted growing interest in distilling CoT capabilities into Small Language Models (SLMs). This study systematically examines the factors influencing CoT distillation, including the choice of granularity, format and teacher model. Through experiments involving four teacher models and seven student models across seven mathematical and commonsense reasoning datasets, we uncover three key findings: (1) Unlike LLMs, SLMs exhibit a non-monotonic relationship with granularity, with stronger models benefiting from finer-grained reasoning and weaker models performing better with simpler CoT supervision; (2) CoT format significantly impacts LLMs but has minimal effect on SLMs, likely due to their reliance on supervised fine-tuning rather than pretraining preferences; (3) Stronger teacher models do NOT always produce better student models, as diversity and complexity in CoT supervision can outweigh accuracy alone. These findings emphasize the need to tailor CoT strategies to specific student model, offering actionable insights for optimizing CoT distillation in SLMs. The code and datasets are available at https://github.com/EIT-NLP/Distilling-CoT-Reasoning.
