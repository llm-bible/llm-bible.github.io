---
layout: publication
title: 'Reinforcement Learning For Aligning Large Language Models Agents With Interactive Environments: Quantifying And Mitigating Prompt Overfitting'
authors: Mohamed Salim Aissi, Clement Romac, Thomas Carta, Sylvain Lamprier, Pierre-yves Oudeyer, Olivier Sigaud, Laure Soulier, Nicolas Thome
conference: "Arxiv"
year: 2024
bibkey: aissi2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19920"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Reinforcement learning (RL) is a promising approach for aligning large
language models (LLMs) knowledge with sequential decision-making tasks.
However, few studies have thoroughly investigated the impact on LLM agents
capabilities of fine-tuning them with RL in a specific environment. In this
paper, we propose a novel framework to analyze the sensitivity of LLMs to
prompt formulations following RL training in a textual environment. Our
findings reveal that the performance of LLMs degrades when faced with prompt
formulations different from those used during the RL training phase. Besides,
we analyze the source of this sensitivity by examining the model's internal
representations and salient tokens. Finally, we propose to use a contrastive
loss to mitigate this sensitivity and improve the robustness and generalization
capabilities of LLMs.
