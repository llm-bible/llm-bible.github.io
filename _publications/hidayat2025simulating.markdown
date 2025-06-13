---
layout: publication
title: 'Simulating Training Data Leakage In Multiple-choice Benchmarks For LLM Evaluation'
authors: Naila Shafirni Hidayat, Muhammad Dehan Al Kautsar, Alfan Farizki Wicaksono, Fajri Koto
conference: "Arxiv"
year: 2025
bibkey: hidayat2025simulating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24263'}
tags: ['RAG', 'Fairness', 'Training Techniques', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Pretraining Methods']
---
The performance of large language models (LLMs) continues to improve, as reflected in rising scores on standard benchmarks. However, the lack of transparency around training data raises concerns about potential overlap with evaluation sets and the fairness of reported results. Although prior work has proposed methods for detecting data leakage, these approaches primarily focus on identifying outliers and have not been evaluated under controlled simulated leakage conditions. In this work, we compare existing leakage detection techniques, namely permutation and n-gram-based methods, under a continual pretraining setup that simulates real-world leakage scenarios, and additionally explore a lightweight method we call semi-half question. Although semi-half offers a low-cost alternative, our analysis shows that the n-gram method consistently achieves the highest F1-score. We also refine these techniques to support instance-level detection and reduce computational overhead. Leveraging the best-performing method, we create cleaned versions of MMLU and HellaSwag, and re-evaluate several LLMs. Our findings present a practical path toward more reliable and transparent evaluations, and we recommend contamination checks as a standard step before releasing benchmark results.
