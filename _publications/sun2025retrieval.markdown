---
layout: publication
title: 'Rearter: Retrieval-augmented Reasoning With Trustworthy Process Rewarding'
authors: Zhongxiang Sun, Qipeng Wang, Weijie Yu, Xiaoxue Zang, Kai Zheng, Jun Xu, Xiao Zhang, Song Yang, Han Li
conference: "Arxiv"
year: 2025
bibkey: sun2025retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.07861'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias']
---
Retrieval-Augmented Generation (RAG) systems for Large Language Models (LLMs)
hold promise in knowledge-intensive tasks but face limitations in complex
multi-step reasoning. While recent methods have integrated RAG with
chain-of-thought reasoning or test-time search using Process Reward Models
(PRMs), these approaches encounter challenges such as a lack of explanations,
bias in PRM training data, early-step bias in PRM scores, and insufficient
post-training optimization of reasoning potential. To address these issues, we
propose Retrieval-Augmented Reasoning through Trustworthy Process Rewarding
(ReARTeR), a framework that enhances RAG systems' reasoning capabilities
through post-training and test-time scaling. At test time, ReARTeR introduces
Trustworthy Process Rewarding via a Process Reward Model for accurate scalar
scoring and a Process Explanation Model (PEM) for generating natural language
explanations, enabling step refinement. During post-training, it utilizes Monte
Carlo Tree Search guided by Trustworthy Process Rewarding to collect
high-quality step-level preference data, optimized through Iterative Preference
Optimization. ReARTeR addresses three core challenges: (1) misalignment between
PRM and PEM, tackled through off-policy preference learning; (2) bias in PRM
training data, mitigated by balanced annotation methods and stronger
annotations for challenging examples; and (3) early-step bias in PRM, resolved
through a temporal-difference-based look-ahead search strategy. Experimental
results on multi-step reasoning benchmarks demonstrate significant
improvements, underscoring ReARTeR's potential to advance the reasoning
capabilities of RAG systems.
