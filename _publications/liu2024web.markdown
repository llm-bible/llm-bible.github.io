---
layout: publication
title: 'WEPO: Web Element Preference Optimization For Llm-based Web Navigation'
authors: Jiarun Liu, Jia Hao, Chunhong Zhang, Zheng Hu
conference: "Arxiv"
year: 2024
bibkey: liu2024web
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10742'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
The rapid advancement of autonomous web navigation has significantly
benefited from grounding pretrained Large Language Models (LLMs) as agents.
However, current research has yet to fully leverage the redundancy of HTML
elements for contrastive training. This paper introduces a novel approach to
LLM-based web navigation tasks, called Web Element Preference Optimization
(WEPO). WEPO utilizes unsupervised preference learning by sampling
distance-based non-salient web elements as negative samples, optimizing maximum
likelihood objective within Direct Preference Optimization (DPO). We evaluate
WEPO on the Mind2Web benchmark and empirically demonstrate that WEPO aligns
user high-level intent with output actions more effectively. The results show
that our method achieved the state-of-the-art, with an improvement of 13.8%
over WebAgent and 5.3% over the visual language model CogAgent baseline. Our
findings underscore the potential of preference optimization to enhance web
navigation and other web page based tasks, suggesting a promising direction for
future research.
