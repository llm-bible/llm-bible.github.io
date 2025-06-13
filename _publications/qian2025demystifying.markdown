---
layout: publication
title: 'Demystifying Reasoning Dynamics With Mutual Information: Thinking Tokens Are Information Peaks In LLM Reasoning'
authors: Chen Qian, Dongrui Liu, Haochen Wen, Zhen Bai, Yong Liu, Jing Shao
conference: "Arxiv"
year: 2025
bibkey: qian2025demystifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02867'}
  - {name: "Code", url: 'https://github.com/ChnQ/MI-Peaks'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code']
---
Large reasoning models (LRMs) have demonstrated impressive capabilities in complex problem-solving, yet their internal reasoning mechanisms remain poorly understood. In this paper, we investigate the reasoning trajectories of LRMs from an information-theoretic perspective. By tracking how mutual information (MI) between intermediate representations and the correct answer evolves during LRM reasoning, we observe an interesting MI peaks phenomenon: the MI at specific generative steps exhibits a sudden and significant increase during LRM's reasoning process. We theoretically analyze such phenomenon and show that as MI increases, the probability of model's prediction error decreases. Furthermore, these MI peaks often correspond to tokens expressing reflection or transition, such as ``Hmm'', ``Wait'' and ``Therefore,'' which we term as the thinking tokens. We then demonstrate that these thinking tokens are crucial for LRM's reasoning performance, while other tokens has minimal impacts. Building on these analyses, we propose two simple yet effective methods to improve LRM's reasoning performance, by delicately leveraging these thinking tokens. Overall, our work provides novel insights into the reasoning mechanisms of LRMs and offers practical ways to improve their reasoning capabilities. The code is available at https://github.com/ChnQ/MI-Peaks.
