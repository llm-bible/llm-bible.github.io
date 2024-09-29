---
layout: publication
title: Pico Peer Review In Llms Based On The Consistency Optimization
authors: Ning Kun-peng, Yang Shuo, Liu Yu-yang, Yao Jia-yu, Liu Zhen-hui, Wang Yu, Pang Ming, Yuan Li
conference: "Arxiv"
year: 2024
bibkey: ning2024peer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01830"}
tags: ['Efficiency And Optimization', 'Survey Paper', 'Training Techniques']
---
Existing large language models (LLMs) evaluation methods typically focus on testing the performance on some closed45;environment and domain45;specific benchmarks with human annotations. In this paper we explore a novel unsupervised evaluation direction utilizing peer45;review mechanisms to measure LLMs automatically. In this setting both open45;source and closed45;source LLMs lie in the same environment capable of answering unlabeled questions and evaluating each other where each LLMs response score is jointly determined by other anonymous ones. To obtain the ability hierarchy among these models we assign each LLM a learnable capability parameter to adjust the final ranking. We formalize it as a constrained optimization problem intending to maximize the consistency of each LLMs capabilities and scores. The key assumption behind is that high45;level LLM can evaluate others answers more accurately than low45;level ones while higher45;level LLM can also achieve higher response scores. Moreover we propose three metrics called PEN CIN and LIS to evaluate the gap in aligning human rankings. We perform experiments on multiple datasets with these metrics validating the effectiveness of the proposed approach.
