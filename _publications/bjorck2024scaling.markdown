---
layout: publication
title: 'Scaling Optimal LR Across Token Horizons'
authors: Johan Bjorck, Alon Benhaim, Vishrav Chaudhary, Furu Wei, Xia Song
conference: "Arxiv"
year: 2024
bibkey: bjorck2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19913"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Scaling Laws']
---
State-of-the-art LLMs are powered by scaling -- scaling model size, dataset
size and cluster size. It is economically infeasible to extensively tune
hyperparameter for the largest runs. Instead, approximately optimal
hyperparameters must be inferred or \textit\{transferred\} from smaller
experiments. Hyperparameter transfer across model sizes has been studied in
Yang et al. However, hyperparameter transfer across dataset size -- or token
horizon -- has not been studied yet. To remedy this we conduct a large scale
empirical study on how optimal learning rate (LR) depends on token horizon in
LLM training. We first demonstrate that the optimal LR changes significantly
with token horizon -- longer training necessitates smaller LR. Secondly we
demonstrate the the optimal LR follows a scaling law, and that the optimal LR
for longer horizons can be accurately estimated from shorter horizons via such
scaling laws. We also provide a rule-of-thumb for transferring LR across token
horizons with zero overhead over current practices. Lastly we provide evidence
that LLama-1 used too high LR, and estimate the performance hit from this. We
thus argue that hyperparameter transfer across data size is an important and
overlooked component of LLM training.
