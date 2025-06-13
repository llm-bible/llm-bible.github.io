---
layout: publication
title: 'Predictable Emergent Abilities Of Llms: Proxy Tasks Are All You Need'
authors: Bo-wen Zhang, Yan Yan, Boxiang Yang, Yifei Xue, Guang Liu
conference: "Arxiv"
year: 2024
bibkey: zhang2024predictable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07111"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Training Techniques', 'Large-Scale Training', 'Scaling Laws']
---
While scaling laws optimize training configurations for large language models
(LLMs) through experiments on smaller or early-stage models, they fail to
predict emergent abilities due to the absence of such capabilities in these
models. To address this, we propose a method that predicts emergent abilities
by leveraging proxy tasks. We begin by establishing relevance metrics between
the target task and candidate tasks based on performance differences across
multiple models. These candidate tasks are then validated for robustness with
small model ensembles, leading to the selection of the most appropriate proxy
tasks. The predicted performance on the target task is then derived by
integrating the evaluation results of these proxies. In a case study on tool
utilization capabilities, our method demonstrated a strong correlation between
predicted and actual performance, confirming its effectiveness.
