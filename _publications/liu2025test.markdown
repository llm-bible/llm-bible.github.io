---
layout: publication
title: 'Metascale: Test-time Scaling With Evolving Meta-thoughts'
authors: Qin Liu, Wenxuan Zhou, Nan Xu, James Y. Huang, Fei Wang, Sheng Zhang, Hoifung Poon, Muhao Chen
conference: "Arxiv"
year: 2025
bibkey: liu2025test
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13447'}
tags: ['GPT', 'Model Architecture', 'Tools', 'Training Techniques', 'Reinforcement Learning']
---
One critical challenge for large language models (LLMs) for making complex
reasoning is their reliance on matching reasoning patterns from training data,
instead of proactively selecting the most appropriate cognitive strategy to
solve a given task. Existing approaches impose fixed cognitive structures that
enhance performance in specific tasks but lack adaptability across diverse
scenarios. To address this limitation, we introduce METASCALE, a test-time
scaling framework based on meta-thoughts -- adaptive thinking strategies
tailored to each task. METASCALE initializes a pool of candidate meta-thoughts,
then iteratively selects and evaluates them using a multi-armed bandit
algorithm with upper confidence bound selection, guided by a reward model. To
further enhance adaptability, a genetic algorithm evolves high-reward
meta-thoughts, refining and extending the strategy pool over time. By
dynamically proposing and optimizing meta-thoughts at inference time, METASCALE
improves both accuracy and generalization across a wide range of tasks.
Experimental results demonstrate that MetaScale consistently outperforms
standard inference approaches, achieving an 11% performance gain in win rate on
Arena-Hard for GPT-4o, surpassing o1-mini by 0.9% under style control. Notably,
METASCALE scales more effectively with increasing sampling budgets and produces
more structured, expert-level responses.
