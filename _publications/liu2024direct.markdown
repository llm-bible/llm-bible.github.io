---
layout: publication
title: 'Direct Large Language Model Alignment Through Self-rewarding Contrastive Prompt Distillation'
authors: Liu Aiwei, Bai Haoping, Lu Zhiyun, Kong Xiang, Wang Simon, Shan Jiulong, Cao Meng, Wen Lijie
conference: "Arxiv"
year: 2024
bibkey: liu2024direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11907"}
tags: ['Distillation', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning']
---
Aligning large language models (LLMs) with human expectations without
human-annotated preference data is an important problem. In this paper, we
propose a method to evaluate the response preference by using the output
probabilities of response pairs under contrastive prompt pairs, which could
achieve better performance on LLaMA2-7B and LLaMA2-13B compared to RLAIF. Based
on this, we propose an automatic alignment method, Direct Large Model Alignment
(DLMA). First, we use contrastive prompt pairs to automatically generate
preference data. Then, we continue to evaluate the generated preference data
using contrastive prompt pairs and calculate a self-rewarding score. Finally,
we use the DPO algorithm to effectively align LLMs by combining this
self-rewarding score. In the experimental stage, our DLMA method could surpass
the \texttt\{RLHF\} method without relying on human-annotated preference data.
