---
layout: publication
title: 'Rewardbench 2: Advancing Reward Model Evaluation'
authors: Saumya Malik, Valentina Pyatkin, Sander Land, Jacob Morrison, Noah A. Smith, Hannaneh Hajishirzi, Nathan Lambert
conference: "Arxiv"
year: 2025
bibkey: malik2025rewardbench
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01937'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
Reward models are used throughout the post-training of language models to capture nuanced signals from preference data and provide a training target for optimization across instruction following, reasoning, safety, and more domains. The community has begun establishing best practices for evaluating reward models, from the development of benchmarks that test capabilities in specific skill areas to others that test agreement with human preferences. At the same time, progress in evaluation has not been mirrored by the effectiveness of reward models in downstream tasks -- simpler direct alignment algorithms are reported to work better in many cases. This paper introduces RewardBench 2, a new multi-skill reward modeling benchmark designed to bring new, challenging data for accuracy-based reward model evaluation -- models score about 20 points on average lower on RewardBench 2 compared to the first RewardBench -- while being highly correlated with downstream performance. Compared to most other benchmarks, RewardBench 2 sources new human prompts instead of existing prompts from downstream evaluations, facilitating more rigorous evaluation practices. In this paper, we describe our benchmark construction process and report how existing models perform on it, while quantifying how performance on the benchmark correlates with downstream use of the models in both inference-time scaling algorithms, like best-of-N sampling, and RLHF training algorithms like proximal policy optimization.
