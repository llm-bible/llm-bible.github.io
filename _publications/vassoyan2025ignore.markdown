---
layout: publication
title: 'Ignore The KL Penalty! Boosting Exploration On Critical Tokens To Enhance RL Fine-tuning'
authors: Jean Vassoyan, Nathanaël Beau, Roman Plaud
conference: "Arxiv"
year: 2025
bibkey: vassoyan2025ignore
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06533'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
The ability to achieve long-term goals is a key challenge in the current
development of large language models (LLMs). To address this, pre-trained LLMs
can be fine-tuned with reinforcement learning (RL) to explore solutions that
optimize a given goal. However, exploration with LLMs is difficult, as a
balance has to be struck between discovering new solutions and staying close
enough to the pre-trained model, so as not to degrade basic capabilities. This
is typically controlled with a Kullback-Leibler (KL) penalty. In this paper, we
investigate the exploration dynamics of a small language model on a simple
arithmetic task. We show how varying degrees of pre-training influence
exploration and demonstrate the importance of "critical tokens" which have a
dramatic impact on the final outcome. Consequently, we introduce a simple
modification to the KL penalty that favors exploration on critical tokens,
increasing the efficiency of the RL fine-tuning stage.
