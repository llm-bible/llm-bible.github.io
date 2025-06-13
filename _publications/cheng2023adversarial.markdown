---
layout: publication
title: 'Adversarial Preference Optimization: Enhancing Your Alignment Via RM-LLM Game'
authors: Pengyu Cheng, Yifan Yang, Jian Li, Yong Dai, Tianhao Hu, Peixin Cao, Nan Du, Xiaolong Li
conference: "Arxiv"
year: 2023
bibkey: cheng2023adversarial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.08045'}
  - {name: "Code", url: 'https://github.com/Linear95/APO'}
tags: ['Has Code', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Human preference alignment is essential to improve the interaction quality of
large language models (LLMs). Existing alignment methods depend on manually
annotated preference data to guide the LLM optimization directions. However,
continuously updating LLMs for alignment raises a distribution gap between
model-generated samples and human-annotated responses, hindering training
effectiveness. To mitigate this issue, previous methods require additional
preference annotation on newly generated samples to adapt to the shifted
distribution, which consumes a large amount of annotation resources. Targeting
more efficient human preference optimization, we propose an Adversarial
Preference Optimization (APO) framework, in which the LLM and the reward model
update alternatively via a min-max game. Through adversarial training, the
reward model can adapt to the shifted generation distribution of the LLM
without any additional annotation. With comprehensive experiments, we find the
proposed adversarial training framework further enhances existing alignment
baselines in terms of LLM helpfulness and harmlessness. The code is at
https://github.com/Linear95/APO.
