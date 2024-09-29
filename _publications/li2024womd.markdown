---
layout: publication
title: Womd-reasoning A Large-scale Language Dataset For Interaction And Driving Intentions Reasoning
authors: Li Yiheng, Ge Chongjian, Li Chenran, Xu Chenfeng, Tomizuka Masayoshi, Tang Chen, Ding Mingyu, Zhan Wei
conference: "Arxiv"
year: 2024
bibkey: li2024womd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04281"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We propose Waymo Open Motion Dataset-Reasoning (WOMD-Reasoning) a language annotation dataset built on WOMD with a focus on describing and reasoning interactions and intentions in driving scenarios. Previous language datasets primarily captured interactions caused by close distances. However interactions induced by traffic rules and human intentions which can occur over long distances are yet sufficiently covered despite being very common and more challenging for prediction or planning models to understand. Therefore our WOMD-Reasoning focuses extensively on these interactions providing a total of 409k Qamp;As for varying types of interactions. Additionally WOMD-Reasoning presents by far the largest Qamp;A dataset on real-world driving scenarios with around 3 million Qamp;As covering various topics of autonomous driving from map descriptions motion status descriptions to narratives and analyses of agents interactions behaviors and intentions. This extensive textual information enables fine-tuning driving-related Large Language Models (LLMs) for a wide range of applications like scene description prediction planning etc. By incorporating interaction and intention language from WOMD-Reasoning we see significant enhancements in the performance of the state-of-the-art trajectory prediction model Multipath++ with improvements of 10.1437; in MR_6 and 6.9037; in minFDE_6 proving the effectiveness of WOMD-Reasoning. We hope WOMD-Reasoning would empower LLMs in driving to offer better interaction understanding and behavioral reasoning. The dataset is available on https://waymo.com/open/download .
