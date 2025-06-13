---
layout: publication
title: 'Probability Consistency In Large Language Models: Theoretical Foundations Meet Empirical Discrepancies'
authors: Xiaoliang Luo, Xinyi Xu, Michael Ramscar, Bradley C. Love
conference: "Arxiv"
year: 2025
bibkey: luo2025probability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08739"}
tags: ['Transformer', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
Can autoregressive large language models (LLMs) learn consistent probability distributions when trained on sequences in different token orders? We prove formally that for any well-defined probability distribution, sequence perplexity is invariant under any factorization, including forward, backward, or arbitrary permutations. This result establishes a rigorous theoretical foundation for studying how LLMs learn from data and defines principled protocols for empirical evaluation. Applying these protocols, we show that prior studies examining ordering effects suffer from critical methodological flaws. We retrain GPT-2 models across forward, backward, and arbitrary permuted orders on scientific text. We find systematic deviations from theoretical invariance across all orderings with arbitrary permutations strongly deviating from both forward and backward models, which largely (but not completely) agreed with one another. Deviations were traceable to differences in self-attention, reflecting positional and locality biases in processing. Our theoretical and empirical results provide novel avenues for understanding positional biases in LLMs and suggest methods for detecting when LLMs' probability distributions are inconsistent and therefore untrustworthy.
