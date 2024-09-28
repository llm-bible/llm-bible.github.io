---
layout: publication
title: PiCO Peer Review in LLMs based on the Consistency Optimization
authors: Ning Kun-peng, Yang Shuo, Liu Yu-yang, Yao Jia-yu, Liu Zhen-hui, Wang Yu, Pang Ming, Yuan Li
conference: "Arxiv"
year: 2024
bibkey: ning2024pico
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01830"}
tags: ['ARXIV', 'LLM', 'Supervised', 'Survey Paper', 'Tools', 'Training Techniques', 'Unsupervised']
---
Existing large language models (LLMs) evaluation methods typically focus on testing the performance on some closed-environment and domain-specific benchmarks with human annotations. In this paper we explore a novel unsupervised evaluation direction utilizing peer-review mechanisms to measure LLMs automatically. In this setting both open-source and closed-source LLMs lie in the same environment capable of answering unlabeled questions and evaluating each other where each LLMs response score is jointly determined by other anonymous ones. To obtain the ability hierarchy among these models we assign each LLM a learnable capability parameter to adjust the final ranking. We formalize it as a constrained optimization problem intending to maximize the consistency of each LLMs capabilities and scores. The key assumption behind is that high-level LLM can evaluate others answers more accurately than low-level ones while higher-level LLM can also achieve higher response scores. Moreover we propose three metrics called PEN CIN and LIS to evaluate the gap in aligning human rankings. We perform experiments on multiple datasets with these metrics validating the effectiveness of the proposed approach.
