---
layout: publication
title: 'WARP: On The Benefits Of Weight Averaged Rewarded Policies'
authors: Alexandre Ramé, Johan Ferret, Nino Vieillard, Robert Dadashi, Léonard Hussenot, Pierre-louis Cedoz, Pier Giuseppe Sessa, Sertan Girgin, Arthur Douillard, Olivier Bachem
conference: "Arxiv"
year: 2024
bibkey: ramé2024benefits
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16768"}
tags: ['Pre-Training', 'Agentic', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement learning from human feedback (RLHF) aligns large language
models (LLMs) by encouraging their generations to have high rewards, using a
reward model trained on human preferences. To prevent the forgetting of
pre-trained knowledge, RLHF usually incorporates a KL regularization; this
forces the policy to remain close to its supervised fine-tuned initialization,
though it hinders the reward optimization. To tackle the trade-off between KL
and reward, in this paper we introduce a novel alignment strategy named Weight
Averaged Rewarded Policies (WARP). WARP merges policies in the weight space at
three distinct stages. First, it uses the exponential moving average of the
policy as a dynamic anchor in the KL regularization. Second, it applies
spherical interpolation to merge independently fine-tuned policies into a new
enhanced one. Third, it linearly interpolates between this merged model and the
initialization, to recover features from pre-training. This procedure is then
applied iteratively, with each iteration's final model used as an advanced
initialization for the next, progressively refining the KL-reward Pareto front,
achieving superior rewards at fixed KL. Experiments with GEMMA policies
validate that WARP improves their quality and alignment, outperforming other
open-source LLMs.
