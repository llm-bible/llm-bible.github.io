---
layout: publication
title: 'Metaphorical User Simulators For Evaluating Task-oriented Dialogue Systems'
authors: Sun Weiwei, Guo Shuyu, Zhang Shuo, Ren Pengjie, Chen Zhumin, De Rijke Maarten, Ren Zhaochun
conference: "Arxiv"
year: 2022
bibkey: sun2022metaphorical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.00763"}
tags: ['Applications', 'Efficiency And Optimization', 'Tools']
---
Task-oriented dialogue systems (TDSs) are assessed mainly in an offline setting or through human evaluation. The evaluation is often limited to single-turn or is very time-intensive. As an alternative, user simulators that mimic user behavior allow us to consider a broad set of user goals to generate human-like conversations for simulated evaluation. Employing existing user simulators to evaluate TDSs is challenging as user simulators are primarily designed to optimize dialogue policies for TDSs and have limited evaluation capabilities. Moreover, the evaluation of user simulators is an open challenge. In this work, we propose a metaphorical user simulator for end-to-end TDS evaluation, where we define a simulator to be metaphorical if it simulates user's analogical thinking in interactions with systems. We also propose a tester-based evaluation framework to generate variants, i.e., dialogue systems with different capabilities. Our user simulator constructs a metaphorical user model that assists the simulator in reasoning by referring to prior knowledge when encountering new items. We estimate the quality of simulators by checking the simulated interactions between simulators and variants. Our experiments are conducted using three TDS datasets. The proposed user simulator demonstrates better consistency with manual evaluation than an agenda-based simulator and a seq2seq model on three datasets; our tester framework demonstrates efficiency and has been tested on multiple tasks, such as conversational recommendation and e-commerce dialogues.
