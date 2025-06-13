---
layout: publication
title: 'On The Modeling Capabilities Of Large Language Models For Sequential Decision Making'
authors: Martin Klissarov, Devon Hjelm, Alexander Toshev, Bogdan Mazoure
conference: "Arxiv"
year: 2024
bibkey: klissarov2024modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05656"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Large pretrained models are showing increasingly better performance in
reasoning and planning tasks across different modalities, opening the
possibility to leverage them for complex sequential decision making problems.
In this paper, we investigate the capabilities of Large Language Models (LLMs)
for reinforcement learning (RL) across a diversity of interactive domains. We
evaluate their ability to produce decision-making policies, either directly, by
generating actions, or indirectly, by first generating reward models to train
an agent with RL. Our results show that, even without task-specific
fine-tuning, LLMs excel at reward modeling. In particular, crafting rewards
through artificial intelligence (AI) feedback yields the most generally
applicable approach and can enhance performance by improving credit assignment
and exploration. Finally, in environments with unfamiliar dynamics, we explore
how fine-tuning LLMs with synthetic data can significantly improve their reward
modeling capabilities while mitigating catastrophic forgetting, further
broadening their utility in sequential decision-making tasks.
