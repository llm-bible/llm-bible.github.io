---
layout: publication
title: 'Optimizing Pretraining Data Mixtures With Llm-estimated Utility'
authors: William Held, Bhargavi Paranjape, Punit Singh Koura, Mike Lewis, Frank Zhang, Todor Mihaylov
conference: "Arxiv"
year: 2025
bibkey: held2025optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11747'}
tags: ['Training Techniques', 'RAG', 'Tools', 'Pretraining Methods']
---
Large Language Models improve with increasing amounts of high-quality
training data. However, leveraging larger datasets requires balancing quality,
quantity, and diversity across sources. After evaluating nine baseline methods
under both compute- and data-constrained scenarios, we find token-count
heuristics outperform manual and learned mixes, indicating that simple
approaches accounting for dataset size and diversity are surprisingly
effective. Building on this insight, we propose two complementary approaches:
UtiliMax, which extends token-based heuristics by incorporating utility
estimates from reduced-scale ablations, achieving up to a 10.6x speedup over
manual baselines; and Model Estimated Data Utility (MEDU), which leverages LLMs
to estimate data utility from small samples, matching ablation-based
performance while reducing computational requirements by \\(\sim\\)200x. Together,
these approaches establish a new framework for automated, compute-efficient
data mixing that is robust across training regimes.
